# 🚀 Performance Testing (JMeter)

## Description

This repository contains performance tests created using JMeter. The tests are organized in test plan files and cover various performance aspects of web applications. The exported JMX files can be easily imported into JMeter for local testing.

## Contents

### 1. JMeter Test Plans

- **File:** [APIPerformanceTest.jmx](https://github.com/kamknap/Performance-Testing/blob/main/APIPerformanceTest.jmx)

- **Description:** This file contains the exported JMeter test plan for API performance testing, including detailed configurations and test scenarios.

- **File:** [GoogleHomePageTestPlan.jmx](https://github.com/kamknap/Performance-Testing/blob/main/GooglePerformanceTests.jmx)

- **Description:** This file contains the exported JMeter test plan for performance testing of the Google homepage, including detailed configurations and test scenarios.

## Test Cases
### API Performance Testing
- **Test Plan:** API performance testing

  - **Thread Group:** Real time users simulation with 10 users and a ramp-up time of 1 second.

  - **API Variables:** Base URL and post data variables.

  - **Sampler:** Create post request to the API.

  - **Assertions:**

    - Verify title of the response.

    - Verify ID of the response.

  - **Listeners:**

    - View Results in Table

    - View Results Tree

## Google Homepage Performance Testing

- **Test Plan:** Google homepage performance testing

    - **Thread Groups:**

      - 10 users accessing the homepage within 10 seconds.

      - 100 users accessing the homepage within 5 seconds.

      - 500 users accessing the homepage within 2 seconds.

  - **Sampler:** GET request to the Google homepage.

  - **Listeners:**

    - View Results in Table

    - View Results Tree

## Purpose

The goal of this repository is to demonstrate my ability to create, organize, and document performance tests using JMeter. The tests cover various scenarios to evaluate the performance of web applications, showcasing my skills in performance testing and analysis.

Feel free to explore the contents of each file for more details.
