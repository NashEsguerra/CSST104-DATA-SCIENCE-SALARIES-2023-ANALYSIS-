<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project: Machine Learning Implementation</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-zu+Q/i5xNNd/YWSiQuFcOGHR6Q2Y3wVGmuyO2cHUb9bsAjfqjFZ5DQ2p5uBPvLf9GzZZmsCjmg+tm/RGr5byWQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="DataScience.css">
</head>
<body>

<div class="title-page">
    <div class="header">
        <i class="fas fa-brain"></i>
        <h1>Final Project: Machine Learning Implementation</h1>
        <i class="fas fa-robot"></i>
    </div>

    <div class="subtitle">
        <i class="fas fa-info-circle"></i>
        <h3>Topic: CSST104 Data Science Salaries 2023 Analysis</h3>
    </div>

    <div class="submitted-by">
        <h3><i class="fas fa-user"></i> Submitted By:</h3>
        <ul>
            <li><i class="fas fa-user-graduate"></i> Magpantay, Niño Jandel C.</li>
            <li><i class="fas fa-user-graduate"></i> Esguerra, Nashrudin Maverick A.</li>
            <li><i class="fas fa-user-graduate"></i> Bautista, Neil Bryan</li>
        </ul>
        <p>BSCS-3B</p>
    </div>
</div>

<div class="ai-ml-section">
    <div class="ai-ml-container">
        <div class="ai-ml-box">
            <i class="fas fa-brain"></i>
            <h3>Artificial Intelligence</h3>
        </div>
        <div class="ai-ml-box">
            <i class="fas fa-robot"></i>
            <h3>Machine Learning</h3>
        </div>
        <div class="ai-ml-box">
            <i class="fas fa-cogs"></i>
            <h3>Data Processing</h3>
        </div>
        <div class="ai-ml-box">
            <i class="fas fa-chart-line"></i>
            <h3>Predictive Analysis</h3>
        </div>
    </div>
</div>





<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Science Salaries 2023 Analysis</title>
    <link rel="stylesheet" href="DataScience.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #001f3f, #005b96);
            color: #ffffff;
        }

        .title-page {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            animation: fadeIn 1s ease-out;
        }

        .title-page .header {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            margin-bottom: 30px;
        }

        .title-page .header i {
            font-size: 3em;
            color: #FFD700;
            transition: transform 0.3s ease;
        }

        .title-page .header i:hover {
            transform: scale(1.2);
        }

        .title-page h1 {
            font-size: 3em;
            color: #FFD700;
            margin: 20px 0;
            text-align: center;
        }

        .title-page .subtitle {
            font-size: 1.5em;
            color: #FFA500;
            text-align: center;
            margin-bottom: 40px;
        }

        .title-page .subtitle i {
            margin-right: 10px;
        }

        .title-page .submitted-by {
            text-align: center;
            color: #ffffff;
        }

        .title-page .submitted-by h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .title-page .submitted-by ul {
            padding: 0;
            margin: 0;
            list-style-type: none;
        }

        .title-page .submitted-by ul li {
            font-size: 1.2em;
            margin-bottom: 5px;
            transition: color 0.3s ease;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .title-page .submitted-by ul li i {
            color: #FFD700;
        }

        .title-page .submitted-by ul li:hover {
            color: #FFD700;
        }

        .title-page .submitted-by p {
            font-size: 1.1em;
            margin-top: 20px;
        }

        /* AI and ML Section */
        .ai-ml-section {
            background-color: #001f3f;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .ai-ml-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .ai-ml-box {
            background-color: #ffffff;
            color: #333333;
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            flex: 1 1 45%;
            max-width: 300px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .ai-ml-box i {
            font-size: 3em;
            color: #005b96;
            margin-bottom: 10px;
        }

        .ai-ml-box:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.3);
        }

        .ai-ml-box h3 {
            font-size: 1.5em;
            margin: 10px 0;
            color: #005b96;
        }

        .ai-ml-box p {
            font-size: 1em;
            color: #666666;
        }

        /* Animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

<div class="title-page">
    <div class="header">
        <i class="fas fa-database"></i>
        <i class="fas fa-database"></i>
    </div>
    <h1>PROJECT OVERVIEW 01</h1>
    <div class="subtitle">
        <strong>Key User Attributes:</strong>
        <p>Work year, Experience Level, Employment Type, Job Title, Salary, Salary Currency, Salary in USD, Employee Residence, Remote Ratio, Company Location, Company Size.</p>
    </div>
</div>

<div class="ai-ml-section">
    <div class="ai-ml-container">
        <div class="ai-ml-box">
            <i class="fas fa-database"></i>
            <h3>LIBRARIES AND DATA HANDLING 02</h3>
            <p>Libraries Used: Pandas, Matplotlib, Seaborn.</p>
            <p>Loading from CSV, data cleaning, handling dates and categorical data.</p>
            <p>This section outlines the libraries used for data analysis and the techniques employed for data loading and preprocessing.</p>
        </div>
        <div class="ai-ml-box">
            <i class="fas fa-chart-bar"></i>
            <h3>DATA ANALYSIS TECHNIQUE 03</h3>
            <p>Descriptive Statistics: Mean, Median, Count, Standard Deviation.</p>
            <p>Visualization Methods: Bar charts, Pie charts, Heatmaps, Count and Distribution plots.</p>
            <p>This section describes the statistical techniques and visualization methods used to analyze the data.</p>
        </div>
        <div class="ai-ml-box">
            <i class="fas fa-search"></i>
            <h3>KEY FINDINGS 04</h3>
            <p>User Demographics: Age and Gender distribution, regional preferences.</p>
            <p>Device Usage: Popular devices from user segment, device-based viewing patterns.</p>
            <p>Subscription Details: Preferences for subscription plans, impact on user engagement.</p>
            <p>This section presents key findings related to
user demographics, device usage, and subscription details.</p>
</div>
<div class="ai-ml-box">
<i class="fas fa-chart-line"></i>
<h3>ADVANCED ANALYSIS 05</h3>
<p>Geographical Insights: Categorization in the continents, regional analysis.</p>
<p>Temporal Trends: Sign-up trends over months, seasonal patterns.</p>
<p>This section provides advanced analysis including geographical insights and temporal trends.</p>
</div>
<div class="ai-ml-box">
<i class="fas fa-robot"></i>
<h3>MACHINE LEARNING 06</h3>
<p>Regression Model: Powerful statistical method for predicting a continuous variable. In the context of our Data Science Salaries 2023 Analysis.</p>
<p>This section discusses the application of a regression model in the analysis of Data Science Salaries 2023.</p>
</div>
<div class="ai-ml-box">
<i class="fas fa-eye"></i>
<h3>VISUAL INSIGHTS 07</h3>
<p>Gender Distribution: Count plots by country, Device preference by country.</p>
<p>Subscription Type Popularity: Visualization of plan popularity.</p>
<p>This section provides visual insights into gender distribution and subscription type popularity.</p>
</div>
<div class="ai-ml-box">
<i class="fas fa-check"></i>
<h3>CONCLUSION 08</h3>
<p>Summary of insights derived, implications for future strategic decisions.</p>
<p>This section summarizes the insights obtained from the analysis and discusses their implications for future strategic decisions.</p>
</div>
<div class="ai-ml-box">
<i class="fas fa-book"></i>
<h3>APPENDIX</h3>
<p>Code Snippets: Provide Python code used for loading, cleaning, transforming data, and generating visualizations.</p>
<p>Google Colab Link: <a href="https://colab.research.google.com/drive/1AeeqrgNwKjYq6nzJuGc4c0Pwd1e9ne3Y">Google Colab Link</a></p>
<p>Datasets: Sample dataset of Data Science Salaries 2023 Analysis.</p>
<p>Additional References: Referenced any external datasets or tools used during the analysis process.</p>
<p>Github Website Link: <a href="https://github.com/NashEsguerra/BSCS-CSST104-DATA-SCIENCE-SALARIES-2023-ANALYSIS.-EMB">Github Website Link</a></p>
</div>
   </div>
    </div>
</div> 
<html lang="en">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analysis and Machine Learning Implementation Project Documentation</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #001f3f, #005b96);
            color: #ffffff;
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
        }

        .content {
            margin-bottom: 30px;
        }

        .content h1, .content h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .content ol {
            padding-left: 20px;
        }

        .content strong {
            color: #FFD700;
        }

        .content p {
            margin-bottom: 10px;
        }

        .content li {
            margin-bottom: 15px;
        }

        .icon {
            margin-right: 10px;
            font-size: 24px; /* Increased icon size */
            color: #FFA500; /* Changed icon color to orange */
        }
    </style>
</head>
<body>
<div class="container">
    <div class="content">
        <h1><i class="fas fa-chart-line icon"></i>Data Analysis and Machine Learning Implementation</h1>
        <h2><i class="fas fa-file-alt icon"></i>Project Documentation Template</h2>
    </div>

    <div class="content">
        <h1><i class="fas fa-info-circle icon"></i>I. Project Overview</h1>
        <p>The analysis aims to explore the determinants of salary in the data science domain by examining various attributes related to data scientists’ employment. Through comprehensive analysis, the project seeks to uncover insights into salary trends, geographical variations, and factors influencing compensation levels within the industry. By investigating key attributes such as work year, experience level, and job title, the project aims to provide actionable insights for both data scientists and employers, guiding career decisions and compensation strategies. Additionally, the analysis will shed light on the impact of employment type, remote work arrangements, and company characteristics on salary disparities, facilitating a deeper understanding of the data science labor market dynamics.</p>

        <ol>
            <li><i class="fas fa-chart-line icon"></i><strong>Work Year:</strong> Analyzing the distribution of data scientists across different years provides insights into industry growth and demand for data science expertise over time. Understanding how salary trends evolve year by year can help anticipate future market conditions and inform hiring and budgeting decisions for employers. For data scientists, insights into salary trends over time can aid in strategic career planning and negotiation strategies.</li>

            <li><i class="fas fa-user-tie icon"></i><strong>Experience Level:</strong> Examining salary variations based on experience level helps identify how experience impacts earning potential within the data science field. Understanding the relationship between experience and salary can guide professional development efforts, such as acquiring additional skills or pursuing advanced degrees. Employers can use this information to establish competitive compensation structures and retention strategies tailored to different experience levels.</li>

            <li><i class="fas fa-briefcase icon"></i><strong>Employment Type:</strong> Analyzing salary differences between full-time, part-time, and contract positions sheds light on employment preferences and their influence on compensation. Understanding how different employment arrangements impact salary can inform workforce planning and recruitment strategies for employers. For data scientists, insights into the trade-offs between employment types and compensation can guide career decisions and lifestyle choices.</li>

            <li><i class="fas fa-briefcase icon"></i><strong>Job Title:</strong> Exploring salary disparities across job titles reveals how specific roles or responsibilities correlate with salary levels, guiding career progression and skill development. Understanding the value assigned to different job titles within the data science field can inform job seekers career trajectories and negotiation strategies. Employers can use this information to benchmark salaries for various roles and ensure equitable compensation across their organization.</li>

            <li><i class="fas fa-money-bill-wave icon"></i><strong>Salary:</strong> The primary focus of the analysis, examining salary distributions, trends, and factors influencing variations in compensation. By identifying factors that contribute to salary discrepancies, such as education, skills, and industry experience, the analysis aims to provide actionable insights for both job seekers and employers. Understanding the factors driving salary variations can help data scientists negotiate competitive compensation packages and employers develop effective hiring and retention strategies.</li>

            <li><i class="fas fa-dollar-sign icon"></i><strong>Salary Currency & Salary in USD:</strong> Converting salaries to a common currency (USD) facilitates uniform comparison and analysis across different regions and currencies. By standardizing salary data, the analysis aims to remove currency-related biases and provide insights that are applicable globally. Understanding salary conversions also helps in assessing the true value of compensation packages and comparing them across international job markets.</li>

            <li><i class="fas fa-globe-americas icon"></i><strong>Employee Residence:</strong> Analyzing salary discrepancies based on employee residence provides insights into geographical factors influencing compensation levels. Understanding how salaries vary across different regions helps both job seekers and employers make informed decisions regarding relocation, remote work opportunities, and cost-of-living adjustments. Insights into regional salary trends also inform talent acquisition strategies, allowing employers to target regions with competitive salary offerings.</li>

            <li><i class="fas fa-wifi icon"></i><strong>Remote Ratio:</strong> Understanding how remote work arrangements impact salary helps in assessing the value of flexibility and remote work policies. By analyzing salary differentials between remote and non-remote positions, the analysis aims to quantify the impact of remote work on compensation levels. Insights into remote work compensation can inform decisions regarding remote work policies, workforce distribution, and talent acquisition strategies.</li>

            <li><i class="fas fa-building icon"></i><strong>Company Location:</strong> Exploring salary discrepancies across different company locations offers insights into regional variations in compensation and cost of living adjustments. Understanding how salaries differ between urban and rural areas, as well as across different countries or states, informs talent acquisition strategies and compensation benchmarking for employers. For data scientists, insights into regional salary trends help in evaluating job opportunities and negotiating competitive compensation packages.</li>

            <li><i class="fas fa-building icon"></i><strong>Company Size:</strong> Analyzing salary trends based on company size illuminates how organizational scale influences salary structures and employment opportunities. By comparing salaries across small, medium, and large companies, the analysis aims to identify potential salary premiums associated with company size and industry competitiveness. Understanding how company size impacts compensation can guide job seekers’ career decisions and employers’ talent acquisition strategies.</li>
        </ol>
        <p>By delving into these attributes,  <p>By delving into these attributes, stakeholders in the data science domain can refine hiring practices and compensation structures, fostering a more equitable and competitive labor market. This meticulous analysis empowers both data scientists and employers with insights crucial for career advancement and organizational growth. Such data-driven decision-making not only optimizes resource allocation and talent acquisition but also cultivates a more vibrant and sustainable data science ecosystem, poised for continuous innovation and excellence.</p>
    </div>
</div>
    
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Libraries and Data Handling</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
<style>
    body {
        font-family: 'Poppins', sans-serif;
        margin: 0;
        padding: 0;
        background: linear-gradient(135deg, #001f3f, #005b96); /* Gradient background */
        color: #ffffff; /* White text color */
    }

    .container {
        max-width: 800px;
        margin: 50px auto;
        padding: 20px;
    }

    .content {
        margin-bottom: 30px;
    }

    .content h1, .content h2 {
        text-align: center;
        margin-bottom: 20px;
    }

    .content ol {
        padding-left: 20px;
    }

    .content strong {
        color: #FFD700;
    }

    .content p {
        margin-bottom: 10px;
    }

    .content li {
        margin-bottom: 15px;
    }

    .icon {
        margin-right: 10px;
        font-size: 24px; /* Increased icon size */
        color: #FFA500; /* Changed icon color to orange */
    }

    .big-icon {
        font-size: 48px; /* Larger icon size */
        color: #FFFF00; /* Yellow icon color */
    }

    .numpy-icon {
        font-size: 24px; /* Font size for NumPy icon */
        color: #FFFF00; /* Yellow color for NumPy icon */
        margin-left: 10px; /* Add margin to the left for spacing */
    }
</style>
</head>
<body>

<div class="container">
<div class="content">
    <h1><i class="fas fa-book-open big-icon"></i> II. Libraries and Data Handling</h1>

    <strong><i class="fas fa-code icon"></i>Libraries Used:</strong>
    <ol>
        <li>
            <strong><i class="fas fa-table icon"></i> Pandas (import pandas as pd):</strong> Pandas is a powerful data manipulation and analysis library in Python. It provides data structures like DataFrame for handling structured data efficiently.
        </li>
        <li>
            <strong><i class="fas fa-chart-bar icon"></i> Seaborn (import seaborn as sns):</strong> Seaborn is a statistical data visualization library built on top of Matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
        </li>
        <li>
            <strong><i class="fas fa-chart-line icon"></i> Matplotlib (import matplotlib.pyplot as plt):</strong> Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.
        </li>
        <li>
            <strong><i class="fas fa-flask icon"></i> NumPy (import numpy as np):</strong> NumPy is a fundamental package for scientific computing with Python. It provides support for arrays, matrices, and mathematical functions.
        </li>
        <li>
            <strong><i class="fas fa-brain icon"></i> Scikit-learn (from sklearn.model_selection import train_test_split, from sklearn.linear_model import LinearRegression, from sklearn.metrics import mean_squared_error, r2_score):</strong> Scikit-learn is a machine learning library that provides simple and efficient tools for data mining and data analysis. It includes various algorithms for classification, regression, clustering, and more.
        </li>
        <li>
            <strong><i class="fas fa-globe icon"></i> Plotly (import plotly.express as px):</strong> Plotly is an interactive, open-source plotting library that supports over 40 chart types and renders charts in various formats, including HTML and PNG images.
        </li>
        <li>
            <strong><i class="fas fa-tools icon"></i> PyCountry (import pycountry):</strong> PyCountry is a package providing ISO databases and information about countries.
        </li>
    </ol>

    <strong><i class="fas fa-tools icon"></i>Data Handling Processes: </strong>Data handling processes involve the collection, storage, manipulation, analysis, and dissemination of data to extract meaningful insights and support decision-making.
    <ul>
        <li><strong><i class="fas fa-cloud-upload-alt icon"></i>Loading Data:</strong> The code starts by loading a dataset from a CSV file using Pandas' read_csv() function.</li>
        <li><strong><i class="fas fa-search icon"></i>Exploratory Data Analysis (EDA):</strong> Various EDA techniques are employed to understand the dataset's structure and characteristics. This includes examining the first and last few rows of the dataset (head() and tail()), checking the shape and columns of the dataset (shape and columns attributes), exploring data types (dtypes), checking unique values in a column (unique()), getting summary statistics (describe()), and handling missing values (using isnull() and visualization via a heatmap).</li>
        <li><strong><i class="fas fa-chart-pie icon"></i>Data Visualization:</strong> Seaborn and Matplotlib are used extensively for data visualization. This includes creating count plots, bar plots, pie charts, histograms, boxplots, line plots, and more to visualize various aspects of the dataset such as salary distribution, job titles, salary trends over the years, salary by different categorical variables, etc.</li>
        <li><strong><i class="fas fa-wrench icon"></i>Data Preprocessing:</strong> Before modeling, the dataset is preprocessed. This involves dropping irrelevant columns, encoding categorical variables using OneHotEncoder, and splitting the data into training and testing sets using train_test_split().</li>
        <li><strong><i class="fas fa-cogs icon"></i>Modeling:</strong> Linear regression modeling is performed using Scikit-learn. The model is trained on the encoded training data, and predictions are made on the test data.</li>
        <li><strong><i class="fas fa-check-circle icon"></i>Evaluation:</strong> Model performance is evaluated using mean squared error (mean_squared_error()) and R² score (r2_score()).</li>
    </ul>
</div>
</div>


   
<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analysis Techniques</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #001f3f, #005b96); /* Gradient background */
            color: #ffffff; /* White text color */
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
        }

        .content {
            margin-bottom: 30px;
        }

        .content h1, .content h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .content strong {
            color: #FFD700;
        }

        .content p {
            margin-bottom: 10px;
        }

        .content ul {
            padding-left: 20px;
            margin-bottom: 20px;
        }

        .content li {
            margin-bottom: 10px;
        }

        .icon {
            margin-right: 10px;
            font-size: 24px;
            color: #FFA500;
        }
    </style>
</head>
<body>


<div class="container">
    <div class="content">
        <h1><i class="fas fa-chart-line icon"></i> III. Data Analysis Techniques</h1>

        <strong><i class="fas fa-info-circle icon"></i> Descriptive Statistics:</strong> Summary statistics like mean, median, count, etc., are used to understand the distribution of data. Descriptive statistics summarize and provide a quick overview of the data through metrics such as mean, median, count, standard deviation, minimum, and maximum values. Here's how they help in the context of Data Science Salaries 2023 Analysis.

        <ul>
            <li><strong><i class="fas fa-chart-bar icon"></i> Mean and Median:</strong> These measures provide insights into the central tendency of numerical data, such as the average salary or years of experience, helping to understand typical values.</li>
            <li><strong><i class="fas fa-check-circle icon"></i> Count:</strong> Counting occurrences of categorical variables like job titles or employee residence countries offers a summary of the dataset's composition.</li>
            <li><strong><i class="fas fa-exclamation-circle icon"></i> Standard Deviation:</strong> This metric quantifies the dispersion or variability of numerical data around the mean, indicating the spread of salaries or other variables in the dataset.</li>
        </ul>

        <strong><i class="fas fa-bullseye icon"></i> Inferential Statistics:</strong> In the context of the provided code snippet, inferential statistics techniques might not be directly evident. However, if applied, they could include hypothesis testing or confidence interval estimation to make predictions or inferences about the population based on sample data.

        <ul>
            <li><strong><i class="fas fa-chart-line icon"></i> Linear Regression:</strong> By fitting a linear model between independent variables like experience level and company size with the dependent variable, salary, linear regression predicts salary based on these factors.</li>
            <li><strong><i class="fas fa-calculator icon"></i> Mean Squared Error (MSE):</strong> This metric quantifies the average squared difference between the predicted and actual salaries, providing a measure of predictive accuracy.</li>
            <li><strong><i class="fas fa-chart-pie icon"></i> R-squared (R2) Score:</strong> R2 score indicates the proportion of variance in the dependent variable (salary) explained by the independent variables, helping to assess the goodness-of-fit of the regression model.</li>
        </ul>

        <h2><i class="fas fa-eye icon"></i> Visualization Techniques:</h2>

        <ul>
            <li><strong><i class="fas fa-chart-bar icon"></i> Bar Chart:</strong> Visualizing job title counts or other categorical variables offers a clear understanding of the distribution and frequency of different categories.</li>
            <li><strong><i class="fas fa-chart-pie icon"></i> Pie Chart:</strong> Representing proportions of categorical variables like job titles or remote ratios provides a concise overview of categorical data distribution.</li>
            <li><strong><i class="fas fa-fire icon"></i> Heat Map:</strong> Mapping missing values in the dataset highlights areas of data incompleteness, aiding in data cleaning and imputation decisions.</li>
            <li><strong><i class="fas fa-chart-line icon"></i> Count Plot:</strong> Count plots are used to display the frequency of observations in categorical variables, such as the count of employees at each experience level or in each company size category.</li>
            <li><strong><i class="fas fa-chart-area icon"></i> Distribution Plots (Histograms and Box Plots):</strong> Histograms and box plots visualize the distribution of numerical variables like salary, showing the range, central tendency, and spread of the data. These plots help in identifying patterns such as skewness, outliers, and central tendency in the dataset.</li>
        </ul>
    </div>
</div>

    
    

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Key Findings</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
        <style>
            body {
                font-family: 'Poppins', sans-serif;
                margin: 0;
                padding: 0;
                background: linear-gradient(135deg, #001f3f, #005b96); /* Gradient background */
                color: #ffffff; /* White text color */
            }
    
            .container {
                max-width: 800px;
                margin: 50px auto;
                padding: 20px;
            }
    
            .content {
                margin-bottom: 30px;
            }
    
            .content h1, .content h2 {
                text-align: center;
                margin-bottom: 20px;
            }
    
            .content strong {
                color: #FFD700;
            }
    
            .content p {
                margin-bottom: 10px;
            }
    
            .content ul {
                padding-left: 20px;
                margin-bottom: 20px;
            }
    
            .content li {
                margin-bottom: 10px;
            }
    
            .content p:first-of-type {
                margin-top: 0;
            }
    
            .icon {
                margin-right: 10px;
                font-size: 24px;
                color: #FFA500;
            }
        </style>
    </head>
    <body>
    
    <div class="container">
        <div class="content">
            <h1><i class="fas fa-chart-bar icon"></i> IV. Key Findings</h1>
    
            <strong><i class="fas fa-user-friends icon"></i> User Demographics:</strong> The dataset likely includes information about the demographics of data scientists such as age, gender, education level, etc. However, these variables are not explicitly analyzed in the provided code.
    
            <ul>
                <li><strong><i class="fas fa-map-marked-alt icon"></i> Employee Residence:</strong> The analysis examines the average salary by employee residence, providing insights into the geographical distribution of salaries. It shows that average adjusted salaries vary based on the country where the employee resides. This suggests that the location of the employee can significantly impact their earning potential.</li>
                <li><strong><i class="fas fa-chart-line icon"></i> Experience Level:</strong> Salary trends are explored concerning experience levels. The count plot illustrates the distribution of data scientists across different experience levels. This insight can help in understanding the demand for data scientists at various career stages and how salary scales with experience.</li>
                <li><strong><i class="fas fa-building icon"></i> Company Location:</strong> The analysis investigates the average salary by company location. It reveals variations in average adjusted salaries across different countries where companies are located. This indicates that the geographical location of the company influences the compensation offered to data scientists.</li>
                <li><strong><i class="fas fa-money-bill-wave icon"></i> Salary:</strong> The analysis includes visualizations depicting salary distributions, trends over the years, and comparisons based on factors like experience level, remote ratio, company size, and employment type. These insights provide a comprehensive understanding of salary dynamics within the dataset.</li>
            </ul>
    
            <p>Findings can influence job title decisions in several ways:</p>
    
            <ul>
                <li><strong><i class="fas fa-users-cog icon"></i> Recruitment Strategy:</strong> Understanding salary trends based on demographics, experience level, and location can guide recruitment strategies. For example, if the goal is to attract experienced data scientists, offering competitive salaries based on market trends can be crucial.</li>
                <li><strong><i class="fas fa-chart-area icon"></i> Market Positioning:</strong> Companies can use salary insights to position themselves competitively in the market. Offering salaries that align with industry standards and considering geographical variations can help attract top talent.</li>
                <li><strong><i class="fas fa-handshake icon"></i> Retention Strategies:</strong> Knowing how salary correlates with factors like experience and location can inform retention strategies. Companies can adjust compensation packages to retain skilled employees, especially in regions or industries where talent is in high demand.</li>
                <li><strong><i class="fas fa-id-badge icon"></i> Job Title Design:</strong> Based on salary insights and demographic trends, companies can design job titles that appeal to their target audience. For example, if the analysis indicates a high concentration of mid-level data scientists in certain regions, creating job titles tailored to this demographic can attract more candidates.</li>
            </ul>
    
            <p>The advanced analysis delves deeper into the dataset's insights, considering various factors such as demographics, experience levels, company and employee locations, and salary dynamics. By examining how these variables interplay with salary trends, the analysis provides valuable insights into recruitment strategies, market positioning, retention initiatives, and job title design. By understanding the nuanced relationships between these factors, companies can make informed decisions to attract, retain, and motivate top talent in the competitive landscape of data science. This advanced analysis goes beyond surface-level observations, offering actionable intelligence to optimize human resource strategies and enhance organizational performance.</p>
        </div>
    </div>
    
    
    
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Advanced Analysis</title>
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
            <style>
                body {
                    font-family: 'Poppins', sans-serif;
                    margin: 0;
                    padding: 0;
                    background: linear-gradient(135deg, #001f3f, #005b96); /* Gradient background */
                    color: #ffffff; /* White text color */
                }
        
                .container {
                    max-width: 800px;
                    margin: 50px auto;
                    padding: 20px;
                }
        
                .content {
                    margin-bottom: 30px;
                }
        
                .content h1, .content h2, .content h3, .content h4 {
                    text-align: center;
                    margin-bottom: 20px;
                }
        
                .content strong {
                    color: #FFD700;
                }
        
                .content p {
                    margin-bottom: 10px;
                }
        
                .content ul {
                    padding-left: 20px;
                    margin-bottom: 20px;
                }
        
                .content li {
                    margin-bottom: 10px;
                }
        
                .content p:first-of-type {
                    margin-top: 0;
                }
        
                /* Make specified section headings light yellow */
                .content h3:nth-of-type(1),
                .content h3:nth-of-type(2),
                .content h4:nth-of-type(1),
                .content h3:nth-of-type(3),
                .content h3:nth-of-type(4) {
                    color: #FFFF00; /* Yellow text */
                }
        
                /* Icon style */
                .icon {
                    margin-right: 10px;
                    font-size: 24px;
                    color: #FFA500; /* Orange color */
                }
            </style>
        </head>
        <body>
        
        <div class="container">
            <div class="content">
                <h1><i class="fas fa-chart-line icon"></i> V. Advanced Analysis</h1>
        
                <h3><i class="fas fa-globe-americas icon"></i> Geographical Insights</h3>
                <ul>
                    <li>The dataset contains information about both company locations and employee residences. By analyzing the average adjusted salary by company location and employee residence, we can gain insights into geographical salary discrepancies.</li>
                    <li>Using choropleth maps and bar plots, we visualize the average adjusted salary across different countries. These visualizations help in understanding regional variations in salary levels, potentially indicating differences in economic development or cost of living.</li>
                </ul>
        
                <h3><i class="fas fa-chart-bar icon"></i> Temporal Trends</h3>
                <ul>
                    <li>Analyzing salary trends over time can reveal valuable insights into the dynamics of the job market and economic conditions.</li>
                    <li>We have explored salary trends over the years, visualizing the average salary against work year. This helps in understanding how salaries have evolved over time and whether there are any significant trends or fluctuations.</li>
                    <li>Additionally, the inflation-adjustment analysis provides a more nuanced view of salary changes over time, considering the impact of inflation rates on salary adjustments. This allows for a more accurate comparison of salary levels across different years.</li>
                </ul>
        
                <h4><i class="fas fa-brain icon"></i> Machine Learning Model</h4>
                <ul>
                    <li>We have applied a linear regression model to predict salaries based on various features. This goes beyond basic descriptive analysis and allows for the exploration of relationships between salary and other factors in a predictive modeling context.</li>
                    <li>By encoding categorical variables and fitting a linear regression model, we aim to understand the factors that influence salary levels and potentially uncover insights that can inform hiring strategies or compensation policies.</li>
                </ul>
        
                <h3><i class="fas fa-chart-line icon"></i> Feature Importance</h3>
                <ul>
                    <li>After fitting the model, we can analyze the feature importance to understand which factors have the most significant impact on salary predictions. This can provide actionable insights for organizations to prioritize certain factors in their hiring or retention strategies.</li>
                </ul>
        
                <h3><i class="fas fa-chart-area icon"></i> Dynamics and Seasonal Patterns</h3>
                <ul>
                    <li>Advanced time series analysis techniques can be applied to uncover seasonal patterns or cyclical trends in salary data. This could involve decomposition methods or autoregressive models to identify recurring patterns and understand their drivers.</li>
                    <li>Exploring correlations between economic indicators and salary levels can provide insights into broader market dynamics and how they impact compensation trends.</li>
                </ul>
        
                <p>By employing these advanced analytical techniques, we can gain a deeper understanding of the factors influencing salary levels, identify geographical disparities, uncover temporal trends, and ultimately derive actionable insights to inform decision-making processes in human resources management and organizational strategy.</p>
            </div>
        </div>
        


    <html lang="en">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Machine Learning Implementation</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #001f3f, #005b96); /* Gradient background */
            color: #ffffff; /* White text color */
        }

        .title-page {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent background for content */
            border-radius: 10px; /* Rounded corners */
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2); /* Shadow effect */
            animation: fadeIn 1s ease-out; /* Fade-in animation */
        }

        .title-page .header {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            margin-bottom: 30px;
        }

        .title-page .header i {
            font-size: 3em;
            color: #FFD700; /* Gold icons */
            transition: transform 0.3s ease; /* Smooth hover effect */
        }

        .title-page .header i:hover {
            transform: scale(1.2); /* Scale effect on hover */
        }

        .title-page h1 {
            font-size: 3em;
            color: #FFD700; /* Gold text */
            margin: 20px 0;
            text-align: center;
        }

        .title-page p {
            font-size: 1.2em;
            text-align: center;
            margin-bottom: 30px;
        }

        /* Make specified section headings light yellow */
        .title-page h1 {
            color: #FFFF00; /* Yellow text */
        }

        /* Animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Machine Learning Implementation</title>
            <style>
                body {
                    font-family: 'Poppins', sans-serif;
                    margin: 0;
                    padding: 0;
                    background: linear-gradient(135deg, #001f3f, #005b96); /* Gradient background */
                    color: #ffffff; /* White text color */
                }
        
                .title-page {
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    align-items: center;
                    height: 100vh;
                    padding: 20px;
                    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent background for content */
                    border-radius: 10px; /* Rounded corners */
                    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2); /* Shadow effect */
                    animation: fadeIn 1s ease-out; /* Fade-in animation */
                }
        
                .title-page .header {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    gap: 20px;
                    margin-bottom: 30px;
                }
        
                .title-page .header i {
                    font-size: 3em;
                    color: #FFD700; /* Gold icons */
                    transition: transform 0.3s ease; /* Smooth hover effect */
                }
        
                .title-page .header i:hover {
                    transform: scale(1.2); /* Scale effect on hover */
                }
        
                .title-page h1 {
                    font-size: 3em;
                    color: #FFD700; /* Gold text */
                    margin: 20px 0;
                    text-align: center;
                }
        
                .title-page p {
                    font-size: 1.2em;
                    text-align: center;
                    margin-bottom: 30px;
                }
        
                /* Make specified section headings light yellow */
                .title-page h1 {
                    color: #FFFF00; /* Yellow text */
                }
        
                /* Animation */
                @keyframes fadeIn {
                    from {
                        opacity: 0;
                        transform: translateY(-20px);
                    }
                    to {
                        opacity: 1;
                        transform: translateY(0);
                    }
                }
            </style>
        </head>
        <body>
        
        <div class="title-page">
            <div class="header">
                <i class="fas fa-cogs"></i>
                <h1>VI. Machine Learning Implementation</h1>
                <i class="fas fa-cogs"></i>
            </div>
            <p>Discuss the data preparation, data selection, data cleaning, and feature scaling implementation. Process of building the machine learning model, including the training and testing sets.</p>
        </div>
        
        
        <html lang="en">
        <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Data Science Salaries Analysis</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
        <style>
        /* Add your CSS code here */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #001f3f, #005b96);
            color: #ffffff;
        }
        
        .title-page {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            animation: fadeIn 1s ease-out;
        }
        
        .title-page .header {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .title-page .header i {
            font-size: 3em;
            color: #FFD700;
            transition: transform 0.3s ease;
        }
        
        .title-page .header i:hover {
            transform: scale(1.2);
        }
        
        .title-page h1 {
            font-size: 3em;
            color: #FFD700;
            margin: 20px 0;
            text-align: center;
        }
        
        /* Add your CSS for other elements here */
        
        h3, h2, p, ul, li {
            margin: 10px 0;
        }
        
        h2, h3 {
            color: #FFD700;
        }
        
        img {
            border: 2px solid #FFD700;
            border-radius: 10px;
            margin: 20px 0; /* Adjusted margin */
            max-width: 100%;
        }
        
        /* Animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        </style>
        </head>
        <body>
        
            <div class="VII. Visual Insights" >
                <div class="container">
                    <div class="content">
                        <i class="fas fa-cogs"></i>
                        <h1>VII. Visual Insights</h1>
                    </div>
                
                    <h3><i class="fas fa-chart-line"></i> Linear Regression Model:</h3>
        
                    <p>Utilizing the Linear Regression model, we aim to predict salaries based on various features such as experience level, company size, and remote ratio. After preparing the data by selecting relevant features, cleaning it to handle missing values and outliers, and scaling features for uniformity, we proceed to build the model. This involves training the model on a portion of the data, splitting it into training and testing sets, and fitting the Linear Regression model to the training data. Evaluation of the model's performance includes assessing metrics like Mean Squared Error (MSE) and R-squared (R²) score, as well as conducting residual analysis to understand the accuracy and potential biases of the model's predictions.</p>
                
                    <<h3><i class="fas fa-database"></i> Preparing the Data for Linear Regression:</h3>
                        <li><strong>Data Selection:</strong> Identify relevant features that contribute to predicting salaries, such as experience level, company size, and remote ratio.</li>
                        <li><strong>Data Cleaning:</strong> Handle missing values, outliers, and ensure data types are appropriate for analysis.</li>
                        <li><strong>Feature Scaling:</strong> Normalize or standardize numerical features to ensure all features contribute equally to the model.</li>
                    </ul>
                <div>
                    <h3>Building the Linear Regression Model:</h3>
                    <ul>
                        <li><strong>Model Training:</strong> Split the dataset into training and testing sets to train the model on a portion of the data and evaluate its performance on unseen data.</li>
                        <li><strong>Splitting Data:</strong> Use techniques like train-test split to divide the dataset into training and testing sets while preserving the distribution of data.</li>
                        <h3><i class="fas fa-cogs"></i> Building the Linear Regression Model:</h3>
         Fit the Linear Regression model to the training data to learn the relationship between features and the target variable (salary).</li>
                    </ul>
                </div>
                  <div>
                   <h3><i class="fas fa-check-circle"></i> Model Evaluation:</h3>
        
                    <ul>
                        <li><strong>Performance Metrics:</strong> Assess the model's performance using metrics like Mean Squared Error (MSE) and R-squared (R²) score to understand how well the model predicts salary.</li>
                        <li><strong>Residual Analysis:</strong> Analyze the residuals (the differences between actual and predicted values) to check for patterns or biases in the model's predictions and identify areas for improvement.</li>
                    </ul>
                    </div>
                  
                  <div>
                  <div>
                    
                        
                    
                        <img src="https://private-user-images.githubusercontent.com/145514134/333618359-185d474b-25f9-4e01-950f-6ef699354da6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTUyMDQsIm5iZiI6MTcxNjc5NDkwNCwicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjE4MzU5LTE4NWQ0NzRiLTI1ZjktNGUwMS05NTBmLTZlZjY5OTM1NGRhNi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzI4MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZWZlNzA0NDQ2YzQ5MDhhODY4NjMwZGM5ZTA1YzcxZjExZDAxODcwMjM2ZjYzOTc3Mzc1MjBlMGFhYjZiNjZkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.aof6BBf5zRzEe6-xOL3BI5hbClk09WMZ-cI8s1AefwY" alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333632540-63cafc85-7fd9-4c88-ae7c-b9984eb1d18d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTUyMDQsIm5iZiI6MTcxNjc5NDkwNCwicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMyNTQwLTYzY2FmYzg1LTdmZDktNGM4OC1hZTdjLWI5OTg0ZWIxZDE4ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzI4MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZGZhZGNiZTJhMzYzN2FlZmU3NDZjOGIxN2RhOGQ2ZWE2Y2MwM2E2ZTA3ODQyYzgwNzBiNGE1N2VmNzI2M2Y1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.8ZylfLptA5iM0OCA6TbfWKghR8Grl05VWp65MnHVnu8" alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333632878-35d11257-d05c-44a4-8972-4b89d4cdd65f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTUyMDQsIm5iZiI6MTcxNjc5NDkwNCwicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMyODc4LTM1ZDExMjU3LWQwNWMtNDRhNC04OTcyLTRiODlkNGNkZDY1Zi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzI4MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iZjUzZTMxZjc2MGZiM2YyYzBjMThmMGViYTIxNGNiNTBkZWU2MDA2NGVkMTNmOGRkM2M1Mzk1ZDQ0MTBiYTMxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.vxrs1QFvfJ2vcYdFAydn6HeO6cJasO_J1hRXLp4tJdw" alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333632935-be715926-b74d-48bd-aea9-555014bf53e4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTUyMDQsIm5iZiI6MTcxNjc5NDkwNCwicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMyOTM1LWJlNzE1OTI2LWI3NGQtNDhiZC1hZWE5LTU1NTAxNGJmNTNlNC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzI4MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wYTEyYzdkMWE5MjIyNTI5MTVhYzAyOTM1YWQxY2JlYjEyYzNkZGQzZWYwMDJiMDhlMTk0MjhlNmEyZjA2ODVmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.KzeO0SeuSsA4lbfIkhlKsQYCgOnom5uTHGVIsMeCIbY" alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333632992-f4cfb61f-d356-4af9-a19a-6a28102a3cc7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMyOTkyLWY0Y2ZiNjFmLWQzNTYtNGFmOS1hMTlhLTZhMjgxMDJhM2NjNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xZDUxYjhjMWM4NjQyZWI0ODgzYjQzMDljZjBjNmMzMTAyMTYyMWFmM2E3YWI4OWMxNDg4YTAyNzZmMmI1MDNiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.NcNpsuLowBpit7w2rUreQLQ6gdwd_N95FG15b7oqApA" alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333633082-d27267f8-263e-41b3-b8fe-6045a9a0df20.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMzMDgyLWQyNzI2N2Y4LTI2M2UtNDFiMy1iOGZlLTYwNDVhOWEwZGYyMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zY2I2M2Y4MWQxZDljNThmODJlODFkNTIyN2E4ZDNlYmExZGRiYzgxY2E5OTk1MGI3MmI3YTkxYmUxYWNmYjZiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.tvV3VXmIkvLffDHig0rotW2MLJcQbJhfsZyJzROxFgQ" alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333633148-9cd3b7b5-f383-4e5c-b9fa-bc0e38161027.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMzMTQ4LTljZDNiN2I1LWYzODMtNGU1Yy1iOWZhLWJjMGUzODE2MTAyNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01Y2U2NTIwZGE1MjAwZDYzOTg2ZmJhMWVmNzQ4OWRlZDExYmQ2YzJhM2MzZTA5YjMyMzU5MDk3YjE4N2E2YmUxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.pE64ZU9ikAcL3pZpww_Ti5SkeqxvKy2qFASqNU1GTto" alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333633236-088cdd1d-cd77-4f54-87f8-0851a153ce23.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMzMjM2LTA4OGNkZDFkLWNkNzctNGY1NC04N2Y4LTA4NTFhMTUzY2UyMy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xYmZhZjIzMzY4ZjkyNzJmZjFmMTkyOTgzM2YwMjNlYTQ5MmViNGQ3MzhkOWEzMjE5YzQ5MjBiMmE5YTA3MjBjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.f72qLiZ8nQtFdscPIfIybrpHojS5loauQ09xAoAiBXs"alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333633366-032c3fcf-cb08-4441-bf30-029237a7d3ab.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMzMzY2LTAzMmMzZmNmLWNiMDgtNDQ0MS1iZjMwLTAyOTIzN2E3ZDNhYi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wOGQ4YmU1OGRmZWEwZDNkYWRmYzgyMGVjMTc0MjgwNzYwYTZmZmNkODQ2NTE1YjMxYWU0ZTIyN2Q2ZWY5NTA1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.5zpKXCgUXB5mq6S88DTWA7xd8iu_V1jaPseG-uAJBXk"alt="Description of the image">
                        <img src="https://private-user-images.githubusercontent.com/145514134/333633428-6e402f1a-259e-42a6-8a86-8c6c1533f365.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjMzNDI4LTZlNDAyZjFhLTI1OWUtNDJhNi04YTg2LThjNmMxNTMzZjM2NS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04NTMwOGQ0NmU3ZDg5MGNmNDhmZWVjMmU0NWMzYzJjNDI2MmZjZjY3YTgyNjVhMTg4YzQ2Nzg3YzgxMWEyMzU3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.xiRRdMP1en6KwzTwPtalzstovIlSBo8Q5aY3IbwNu8o"alt="Description of the image">                            
                 
                    <div>
                 
                    <div>
            
                      
                <h1>Implementing the Model with Code Example</h1>
                   <h2><i class="fas fa-file-import"></i>1. Import Libraries</h2>
        
                    <img src="https://private-user-images.githubusercontent.com/145514134/333612535-ade1543c-cd2d-4dcb-b33c-2848ff9a5a75.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjEyNTM1LWFkZTE1NDNjLWNkMmQtNGRjYi1iMzNjLTI4NDhmZjlhNWE3NS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03MmE2ODU1NmI0MzMzYjMxMGQzZTdiNjAwODQyYThlZjRkZDgzY2EzZjUxZTU0NmY3ZmFiNDVlZWY4MjY0NjNjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.xPOlh22-Zvyk50SfLJgWKBHBjMXetAZH7VKKnTwpqPg" alt=" Import Libraries" width="600">
                
                
                    <h2><i class="fas fa-database"></i>2. Numerical Data</h2>
        
                    <img src="https://private-user-images.githubusercontent.com/145514134/333612597-4eb9d5c8-bf0b-4eda-81c7-05506fe90bd7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjEyNTk3LTRlYjlkNWM4LWJmMGItNGVkYS04MWM3LTA1NTA2ZmU5MGJkNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04YzJlODBkZDczNzNlZWJkN2NmNjhiYjkxYzVkMDg1NTQ3ZDI0MTE2ZjdiMzljZDVkODExZWEzMTlmMGM0ZTFhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.zhxqq-s-XvZ27ZgrgJNGAVPIPPfRPgazigHecijz_RY" alt="Numerical Data" width="600">
                
                     <h2><i class="fas fa-dice"></i>3. Splitting the dataset into the training set and test set</h2>

                    <img src="https://private-user-images.githubusercontent.com/145514134/333612801-a0d6cdeb-f2ae-4c99-b335-50f53d928eaa.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjEyODAxLWEwZDZjZGViLWYyYWUtNGM5OS1iMzM1LTUwZjUzZDkyOGVhYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zZDNhYzA4NTk4ODhlOWY2MzgzYjk1MzVhZGEzZmNkNTUyZmUyYzE1NjdkOTNhODc4YzM0NjVmY2FhZjU5NWU2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.73bt_rM4SwWcvH59qWGDWvnB22Z6yNqjALV1FquZVkg" alt="Splitting Dataset" width="600">
                
                   <h2><i class="fas fa-cogs"></i>4. Initialize the Linear Regression Model</h2>
        
                    <img src="https://private-user-images.githubusercontent.com/145514134/333612866-00482451-5347-4433-91f6-cc1dea86c0ea.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjEyODY2LTAwNDgyNDUxLTUzNDctNDQzMy05MWY2LWNjMWRlYTg2YzBlYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yZjE1MDY2ZjEzNDA3MTUwNjlmYjlkNGQ4N2EyOGU0YzU2MDRkYWNiMjcyZGQ5YTYwZWUxZjRhNDM2Yzk5ZjMyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.AK7EOpeIzcPQT6mn_64_vpIlOFf4VDxNIXeSh62RZ18" alt="Initializing Linear Regression Model" width="600">
                
                    <h2><i class="fas fa-play"></i>5. Fit the model</h2>
        
                    <img src="https://private-user-images.githubusercontent.com/145514134/333613084-e100716c-009d-4c34-9c32-f8f69980886a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjEzMDg0LWUxMDA3MTZjLTAwOWQtNGMzNC05YzMyLWY4ZjY5OTgwODg2YS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jNTk4MmVkNGUwMmFjNGUxYmFlZmU5MTg0NmNkYjYwNGM0ODc2ZDc0ZTNiM2U5MWI3MmIwOTBiOWJmODk0NmExJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.tkeATxAgbzODtI5RqDG1UrynZPVTIrQ2sCUX4ksxSfY" alt="Fit the model" width="600">
                
                   <h2><i class="fas fa-lightbulb"></i>6. Predict on the testing set</h2>
        
                    <img src="https://private-user-images.githubusercontent.com/145514134/333613129-c2b5ccdb-f699-46a3-86c5-0466633f5321.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjEzMTI5LWMyYjVjY2RiLWY2OTktNDZhMy04NmM1LTA0NjY2MzNmNTMyMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hM2I0NjI0Y2ViMzRhOGUzZDdiNmU2YjEwZDVjZjIxZTZkY2I5ZDllZDlhMjQ1Nzc4ODQ1YmVkMDA1ZDMxNzM3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.FZOSCWngcuYc0FmBYcEqUMIOwd5CZOXUDW4nryEZTY4" alt="Predict on the testing set" width="600">
                
                   <h2><i class="fas fa-check"></i>7.Evaluate the model</h2>
        
                    <img src="https://private-user-images.githubusercontent.com/145514134/333613236-c2881ad6-1858-4d0f-86ac-ad2af13bc9a6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY3OTU1MTcsIm5iZiI6MTcxNjc5NTIxNywicGF0aCI6Ii8xNDU1MTQxMzQvMzMzNjEzMjM2LWMyODgxYWQ2LTE4NTgtNGQwZi04NmFjLWFkMmFmMTNiYzlhNi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyN1QwNzMzMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zNDY5ODUyNWE2Mjk2NTJmMDY3YWVmMzc2MDNhNmEwODA3ZTBmM2UyMjI0ODcyMDg1MWY4NGU2NDU5ZjdiMzQ4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.DobpBD04GKv2hm1Lh5fJ_63lT1g80O7444-CRyNIDwY"alt="Evaluate the model" width="600">
                </div>
            </div>
            
    
    
    
           
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <title>Data Science Salaries 2023 Analysis</title>
                <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
            </head>
            <body>
            
            <div class="content">
                <h1><i class="fas fa-chart-line" style="color: yellow;"></i> VIII. Conclusion</h1>

                <p>In this analysis, we explored a dataset containing information about salaries of data scientists, examining various factors influencing salary trends. Through visualization and statistical analysis, we gained insights crucial for businesses and organizations employing data scientists.</p>
            
                <p>Firstly, we observed the distribution of salaries across different experience levels, remote work ratios, company sizes, and employment types. This comprehensive analysis provided a nuanced understanding of how these factors correlate with salary variations. Additionally, we identified the top 10 job titles and their corresponding salary distributions, illuminating roles commanding higher compensation in the data science field.</p>
            
                <p>Moreover, we investigated the relationship between salary and other variables such as work year, experience level, remote work ratio, and company size. These analyses revealed insights into how these factors collectively influence salary levels.</p>
            
                <p>Additionally, we addressed the impact of inflation on salaries, offering a method to adjust salaries based on inflation rates to ensure fair compensation over time. Furthermore, leveraging geographical insights, we explored average salaries by company location and employee residence, highlighting regional disparities in data scientist salaries.</p>
            
                <p>This analysis underscores the importance of data-driven decision-making in human resources and organizational planning. By understanding the factors influencing data scientist salaries, businesses can make informed decisions regarding recruitment, retention, and compensation strategies.</p>
            
                <p>Moving forward, further analysis could explore additional factors such as educational background, specific skill sets, industry domains, and certification levels to gain a more granular understanding of salary determinants in the data science landscape. Additionally, longitudinal studies tracking salary trends over time could provide valuable insights into industry dynamics and economic shifts.</p>
            
                <h2><i class="fas fa-file-alt"></i> Appendix</h2>
            
                <h3><i class="fas fa-database"></i> Data Sources:</h3>
                <ul>
                    <li>The dataset used for analysis and modeling is sourced from "DataScientiestSalaries.csv".</li>
                    <li>Inflation rates used for adjusting salaries are provided within the code as dictionaries (us_inflation_rates and global_inflation_rates).</li>
                </ul>
            
                <h3><i class="fas fa-users"></i> Contributor Details:</h3>
                <ul>
                    <li>Analysis, visualization, and modeling code written by [Magpantay, Esguerra, Bautista].</li>
                    <li>Data cleaning, preprocessing, and manipulation may have been performed by [Magpantay, Esguerra, Bautista].</li>
                </ul>
            
                <h2><i class="fas fa-laptop-code"></i> Data Science Salaries 2023 Analysis Using Python</h2>
            
                <p><i class="fas fa-link"></i>  Program: 
                    <a href="https://colab.research.google.com/drive/1AeeqrgNwKjYq6nzJuGc4c0Pwd1e9ne3Y#scrollTo=VCI2JIUBux9q&printMode=true" style="color: red;">Colab Link</a>
                </p>
                
                <p><i class="fas fa-link"></i>  Datasets: 
                    <a href="https://drive.google.com/file/d/13P7JQj1vPx6D92X1KuMReBr8DseoVSnO/view?usp=sharing" style="color: red;">Google Drive Link</a>
                </p>
                
            
            </body>
            </html>
