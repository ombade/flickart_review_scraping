# Web Scraping Project: Reviews Scraping from Flipkart.com

Hello everyone,

I'm excited to share that I have successfully deployed my first project on AWS (Amazon Web Services), and I couldn't be more thrilled about it! 🚀

## Overview

For this project, I developed a powerful web scraping application that extracts valuable reviews from Flipkart.com, one of India's leading e-commerce platforms. The objective was to collect and analyze customer feedback, helping businesses make data-driven decisions and enabling consumers to make informed purchasing choices.

## Technologies Used

The project leveraged cutting-edge technologies to ensure efficiency, scalability, and a smooth user experience:

- **Flask**: The web application's backend was developed using Flask, a lightweight Python web framework. Flask provided a simple and intuitive interface for users to interact with the web scraping process.

- **Python**: As the driving force behind the application, Python facilitated the implementation of web scraping algorithms and data processing.

- **Beautiful Soup**: This Python library played a pivotal role in parsing HTML and XML documents, allowing the extraction of relevant review information from Flipkart's web pages.

- **MongoDB Atlas**: To ensure efficient data storage and retrieval, I integrated MongoDB Atlas as the database for this project. Its NoSQL architecture allowed seamless handling of unstructured review data.

- **AWS (Amazon Web Services)**: For hosting the web application, I utilized AWS services. Specifically, I used Elastic Beanstalk, a Platform-as-a-Service (PaaS) offering, to manage application deployment, scaling, and automatic load balancing.

- **CodePipeline**: To streamline the deployment process and maintain continuous integration and continuous delivery (CI/CD), I established a seamless pipeline between GitHub and AWS using CodePipeline. This enabled automatic deployment of updates whenever new code changes were pushed to the GitHub repository.

## Web Scraping Process

The web scraping application utilizes the power of Python and Beautiful Soup to crawl through Flipkart.com and extract valuable reviews for various products. Here's a high-level overview of the scraping process:

1. **Product URLs Collection**: The application starts by collecting URLs of product pages from Flipkart's search results based on user-defined search criteria (e.g., product category, keyword).

2. **Scraping Reviews**: For each product URL, the application visits the page and extracts the customer reviews, including the reviewer's name, rating, review text, and other relevant details.

3. **Data Cleaning**: The extracted data may contain noise and irrelevant information. To ensure high-quality data, the application performs data cleaning and filtering to retain only valid reviews.

4. **Data Storage**: The clean review data is then stored in the MongoDB Atlas database for further analysis and retrieval.

## Acknowledgments

I would like to express my heartfelt gratitude to Vishwa Mohan for providing valuable guidance throughout the project. Your insights were instrumental in shaping this application.

Special thanks to Ayush Pujari for his exceptional problem-solving skills. Your timely assistance in resolving errors made a significant difference.

## Explore the Project

I invite you all to check out the live version of my project at: http://webscrapingflikart-env.eba-3ddsmpz3.us-east-1.elasticbeanstalk.com/

For those who are interested in exploring the technical details and code implementation, feel free to visit my GitHub repository: [[GitHub Repo](https://your-github-repo-url.com)](https://github.com/ombade)

## Get Inspired!

I hope my project inspires you and serves as a valuable learning resource for your own endeavors. Please feel free to share your thoughts and feedback. Thank you for your support! 😊🙏

### Project Tags

AWS, Web Scraping, Python, Flask, MongoDB, CodePipeline, GitHub, Data Collection, Web Development, Tech Projects, Gratitude

