# List of Project Proposals

- [Machine Learning](#machine-learning)
  * [1. Your Own Machine Learning Library](#1-your-own-machine-learning-library)
  * [2. Machine Learning Model Zoo](#2-machine-learning-model-zoo)
  * [3. Sentiment Analysis on #lgbt tweets](#3-sentiment-analysis-on-lgbt-tweets)
  * [4. Style Transfer on Images](#4-style-transfer-on-images)
- [Web Development](#web-development)
  * [1. Bookmark Manager Web extension](#1-bookmark-manager-web-extension)
  * [2. Note Board](#2-note-board)
  * [3. Newsroom (Website)](#3-newsroom-website)
- [Android App Development](#android-app-development)
  * [1. Shared Calendar](#1-shared-calendar)
  * [2. Newsroom (Android App)](#2-newsroom-android-app)
  * [3. Attendance Manager](#3-attendance-manager)

# Machine Learning

## 1. Your Own Machine Learning Library

- **Suggested Audience:** First years and above
- **Description:** One of the crucial things in machine learning is to understand the inner working of the  algorithms being used. In this project, you will develop a machine learning library consisting of various machine learning algorithms built without using any ready-to-use library. A tentative list of algorithms can be discussed later with the mentors.

- **Goals:** 
  - Phase 1: Implementation of linear regression, logistic regression, decision tree, k-nearest neighbours, K-means clustering, neural networks.
  - Phase 2: Implementation of more advanced algorithms and techniques, if time permits.

- **Requirements:** 
  - Basic knowledge of machine learning algorithms.
  - Basic knowledge of Python, object-oriented programming and Numpy.
- **Resources:** 
  - A basic overview of the algorithms is given [here](https://www.analyticsvidhya.com/blog/2017/09/common-machine-learning-algorithms/).

## 2. Machine Learning Model Zoo

- **Suggested Audience:** First years and above
- **Description:** A model zoo is a collection of machine learning models trained and applied for various problems ranging from simple regression to large scale vision problems. In this project, you will create machine learning models for various regression as well as classification tasks. 

- **Goals:** 
  - Phase 1: Implementation of machine learning models for various regression tasks. You can choose tasks of your own or discuss with the mentors.
  - Phase 2: Implementation of more advanced machine learning models for classification tasks on image data.

- **Requirements:** 
  - Implementation knowledge of machine learning algorithms.
  - Knowledge of Python, basic understanding of Numpy and Scikit-Learn. Knowledge of Pandas would be an  advantage.
- **Resources:** 
  - A basic overview of the algorithms is given [here](https://www.analyticsvidhya.com/blog/2017/09/common-machine-learning-algorithms/).
  - An article on difference between regression and classification is given [here](https://www.geeksforgeeks.org/regression-classification-supervised-machine-learning/).

## 3. Sentiment Analysis on #lgbt tweets

- **Suggested Audience:** First years and above
- **Description:**  Sentiment analysis is the process of identifying and categorizing opinions expressed in a piece of text. #lgbt spread virally in 2018 as a hashtag when the Supreme Court of India decriminalised homosexuality by declaring Section 377 of the Indian Penal Code unconstitutional. This project will try to predict the sentiment from the tweets with the #lgbtq hashtag.

- **Goals:** 
  - Phase 1: Scrape the tweets from Twitter with the hash tag #lgbt and store the data locally.
  - Phase 2: Train a sentiment analysis model separately and use it to predict the sentiments for the gathered tweets. Additionally, you can try to suggest if a user requires social counselling based on the intensity of the sentiment.

- **Requirements:** 
  - Knowledge of scraping tools such as scrapy, BeautifulSoup and advanced string matching tools like regex.
  - Conceptual knowledge of Natural Language Processing.
  - Programming skills in Python and ready-to-use machine learning libraries like scikit-learn.

## 4. Style Transfer on Images

- **Suggested Audience:** First years and above
- **Description:** Ever wished you could paint like Picasso or Van Gogh? Now, it is possible for a Deep Learning enthusiast like you by using the art of Neural Style Transfer. Style transfer is the technique of recomposing images in the style of other images.

- **Goals:** 
  - Phase 1: Implementation of the paper “A Neural Algorithm of Artistic Style” by Leon A. Gatys et al.
  - Phase 2: Implement Neural Style Transfer for a practical use.

- **Requirements:** 
  - Conceptual knowledge of Deep Learning, specifically Convolutional Neural Networks.
  - Strong programming skills in Python and knowledge of a Deep Learning framework (Tensorflow/ Keras/ PyTorch) would be helpful.
- **Resources:** 
  - [Link](https://arxiv.org/pdf/1508.06576.pdf) to the paper "A Neural Algorithm of Artistic Style” by Leon A. Gatys et al.
  - A working demo of Neural Style Transfer can be found [here](https://deepart.io/).

# Web Development

## 1. Bookmark Manager Web extension

- **Suggested Audience:** First year and Second Year
- **Description:** A web extension which is used to manage bookmarks having these features (but not limited to)-
  1. The user can search in bookmarks (for the title, URL)
  2. User can save notes along with bookmarks for future references.
  3. Users can export all the data (including notes) to a separate json file.

- **Goals:** 
  - Build the chrome extension up to completion/adequate progress.

- **Requirements:** 
  - Basic knowledge of HTML, CSS and JavaScript
  - Fuzzy search can be implemented for searching
- **Resources:**
  - Refer the tutorial [here](https://developer.chrome.com/extensions/getstarted) on how to build a chrome extension.
  
## 2. Note Board

- **Suggested Audience:** First year
- **Description:** A note scribbling website which will just be a full size textfield with a save button having these features (but not limited to) -
  1. Clicking anywhere should start typing from that point (similar to One Note).
  2. A save button will persist the text to a Database.
  3. Visiting the website from anywhere should show the same text.

- **Goals:** 
  - Phase 1: Build the frontend UI and logic for the application.
  - Phase 2: Add users and database persistance feature to the application.

- **Requirements:** 
  - Basic knowledge of HTML, CSS and JavaScript
  - Basic knowledge of database persistance.
  
- **Resources:**
  - Firebase Database can be used. It persists data without having to write backend code ([docs](https://firebase.google.com/docs/database/web/start), [tutorial](https://www.tutorialspoint.com/firebase/)).
  
## 3. Newsroom (Website)

- **Suggested Audience:** First year
- **Description:** A website in which each club/student chapter of our college will have a page through which people can subscibe. Allow clubs/student chapters to register if they have a Facebook page. The app will fetch latest information posted on the actual Facebook page and show it in the newsroom page, provide notifications etc.

- **Goals:** 
  - Phase 1: Build the frontend for the app.
  - Phase 2: Using Facebook Graph API, fetch the posts from the respective Facebook pages and add subscription system.

- **Requirements:** 
  - Knowledge of HTML, CSS and Javascript.
  - Knowledge of a backend language and database persistence.
  - Basic Knowledge of Facebook's Graph API.
  
- **Resources:**
  - Refer the Graph API documentation: [Graph API Docs](https://developers.facebook.com/docs/graph-api)


# Android App Development

## 1. Shared Calendar

- **Suggested Audience:** First Year and above
- **Description:** Shared calendar is an android app to solve the problem of clashes of student activities in the college. Each club can highlight the dates when they will be conducting some major session/workshop so that other clubs can view and plan their sessions/workshops accordingly.

- **Goals:** 
  - Phase 1: Build the frontend for the app.
  - Phase 2: Add the login and data persistence features.

- **Requirements:** 
  - Knowledge of Java, XML and Android basics.
  - Knowledge of database persistence.
  
## 2. Newsroom (Android App)

- **Suggested Audience:** First year and above
- **Description:** An android app in which each club/student chapter of our college will have a tab/page through which people can subscibe. Allow clubs/student chapters to register if they have a Facebook page. The app will fetch latest information posted on the actual Facebook page and show it in the newsroom page, provide notifications etc.

- **Goals:** 
  - Phase 1: Build the frontend for the app.
  - Phase 2: Using Facebook Graph API, fetch the posts from the respective Facebook pages and add subscription system.

- **Requirements:** 
  - Knowledge of Java, XML and Android basics.
  - Knowledge of networking and database persistence.
  
- **Resources:**
  - Refer the Graph API documentation: [Graph API Docs](https://developers.facebook.com/docs/graph-api)
  
## 3. Attendance Manager

- **Suggested Audience:** First year and above
- **Description:** An android app which helps you keep track of your daily attendance in classes.
Just select whether you were present or absent in a particular class everytime that subject's class occurs and get informed about the current percentage, total number of days absent, etc. while saving the current status of attendance so that it can be accessed later. There should be various features like add/delete subject, edit attendance, change minimum attendance criteria, reset attendance, etc.

- **Goals:** 
  - Phase 1: Build the frontend for the app.
  - Phase 2: Store all the information in local storage.

- **Requirements:** 
  - Knowledge of Java, XML and Android basics.
  - Knowledge of SQLite or Room.
  
- **Resources:**
  - Refer the SQLite documentation: [SQLite Docs](https://developer.android.com/training/data-storage/sqlite)
  - Refer the Room documentation: [Save data in a local database using Room](https://developer.android.com/training/data-storage/room/)
