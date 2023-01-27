# Udhamini Web Application
“Udhamini” is a Swahili word for guarantee. Udhamini web app is a platform that lets all students get access to a centralized repository of scholarships and apply for them. This bridges the gap between students searching for scholarships online and missing opportunities some of them due to the deadline.

## The team
Team Score More is a group of innovative students who are focused on solving scholarships problem in our society. In the past, we have all had our struggles in paying for education, some of us being forced to differ from school and retake a semester another time. We supported each other through these hard times and decided to come up with the idea to create a scholarship system which would help make the experience a lot better for other students like us in society.

1. Kevin Comba Gatimu - Kirinyaga University
BSc. Computer Science, Grad. 2023 - Software engineer who is an advocate of web development and cross-platform UI software solutions. – Team Lead.

2. Samuel Kamotho - Kirinyaga University
BSc. Computer Science, Grad. 2023 - Software developer and a Microsoft Learn student ambassador. Values creating impactful solutions

3. Denis Wachira Kathuri - Kirinyaga University
BSc. Computer Science, Grad. 2025 – Database Engineer, passionate about using Azure cloud computing solutions.

4.Charity Jelimo - Kirinyaga University 
BSc. Software Engineering, Grad. 2024 – Frontend developer, passionate about using Azure cloud computing solutions.

## The Concept 
Close to 1 million students will sit for the High school exams this year. Despite the high numbers, only a few join tertiary institutions of learning due to a shortage of funds to facilitate education, despite having fared well in the national exams. Some of them join the universities but drop out of school later due to lack of upkeep funds and school fees. This also leads to students differing from their studies, yet they are not aware of the available opportunities which can support their financial needs to access education.

The proposed system aims to achieve the following objectives;

1. Create a well-structured, centralized scholarship data repository to facilitate storage, querying, and access.
2. Reduce the time it takes to search for and visit scholarship websites to access scholarship application forms.
3. Assist students who are unable to pursue education because of financial constraints.

## Target Audience or Market:
Our main audience is Junior high school (primary school) graduates, Senior high school (secondary school) graduates, and university and college, students. According to an article published by the university of Eldoret, education is costly in Kenya. A student is required to spend approximately Ksh. 100,000 on tuition fees in one academic year to earn a bachelor's degree. Many households in Kenya struggle to raise funds to cater to the basic needs for university students
Endesia, Nicholas Munyasi (2021). Unit cost of university education and its economic implication for university students. http://erepository.uoeld.ac.ke/handle/123456789/1032

> In Kenya, the hope of 45,000 students, who did the 2020 Kenya Certificate of Primary Education (KCPE) exams in March 2021, to get full scholarships for secondary education were shattered. Only 9000 students among 54,000 who applied for the Elimu Scholarship Program were selected to benefit from the scholarship. The statistics show that 83% of these students did not get any school fee aid and struggled to get their foot in tertiary learning institutions.

  [Brian Mbuvi, (21 July 2021). 45,000 Form 1 Students Miss Scholarships](https://www.kenyans.co.ke/news/66770-45000-form-1-students-miss-scholarships)

## Personas

 - Persona 1: John, dreams to be an entrepreneur.
 
    • Name: John Shaw
    
    • Occupation: Senior high school graduate.
    
    • Demographic: 19 years old, lives in Nairobi. Born in a family of 6 siblings. Three of his siblings are in junior high school and two are in senior high school.         His parents’ occupation is small-scale farming.
  
  - Persona 2: Rebecca, dreams to be a Microsoft Cloud Advocate.
  
    • Name: Rebecca Stone

    • Occupation: University Student

    • Demographic: 22 years old, lives in Kirinyaga. Born in a family of 3 siblings. Brought up by a single parent. Her parent is struggling to raise the pending school fee balance for the current semester

## Feedback

• Felix Omuok [Software Engineer at Microsoft]

The level of confidence is good generally, include some PowerPoint slides as well to help support your arguments; doing so will also help you organize your presentation better.

• Julia Muiruri [Cloud advocate at Microsoft]

Strong idea,

## How it works:
<img width="1074" alt="Drawing" src="https://user-images.githubusercontent.com/57180726/215202501-5408c3a7-2a6f-4fcc-ade0-68fd70aa57c3.png">


This web Application allows the user to register and create a portal. Using his/her portal, the user can access a collection of scholarships fetched from the Azure Cosmos DB via the API. Azure Cosmos Database gets populated with scholarships from the internet via a web scrapping engine. The web application, API and web scraping Engine are hosted By Azure via Azure app services while the database runs on Azure cosmos Database. We use GitHub CI/CD to continually add new features to the web app, API and web scraping engine.

## Core Technologies

This web application is composed of a Frontend User Interface built with react.js, backend API built with Node.js and express.js, Azure Front Door CDN to make sure our app is routing correctly, Azure Cosmos Db which is the storage and Web scraping Engine using JavaScript. Below is a table to show each component of the application and the Azure resource which is powering it up.

| App Component      | Powered by |
|--------------------|------------|
| Frontend UI        | Azure Static Web App     |
| Backend API        | Azure Services     |
| App CDN        | Azure Front Door and CDN Profiles     |
| Database       | Azure Cosmos DB for MongoDB     |
| Images Storage       | Azure Storage Account     |

## The Business Plan:

The app will generate income primarily through members’ subscriptions on a monthly or annual basis. The app will have 2 subscription tiers, free, premium. The free tier will limit students to a small number of scholarships while the premium tier will offer all available scholarships.

## Competition:

  1. Most systems have several drawbacks, including the fact that they only provide scholarships from their own organizations, preventing users from applying for scholarships from other sponsors. Since most scholarships are awarded based on nominations, your chances of winning increase as the number of nominations increases. This keeps most students with a low nomination count from receiving scholarships without considering their tuition and maintenance requirements.

  2. Some systems give rewards to students who get an A, start a new club, or do something noteworthy in high school. This method is not a one-stop shop for scholarships because it only offers a small number of chances.

  3. Other scholarship search platform has partnered with high schools across the country and custom match you with scholarships based on your demographics, age, interests, and more. You’ll be able to apply for many of their opportunities directly on their site, and they have a thorough process for vetting the opportunities they post. They use a more thorough vetting process than many of their competitors, hence hindering equal opportunities for all applicants

## Business Model

Our project will have three business model strategies,

  1. Affiliate marketing – As Score more team, we have a plan to ensure that we reach millions of students. To make this a success, we are planning to use affiliate companies to market e.g., use it in social media apps, hosting platforms example hostinger, freelancing site e.g., fiver and many more.
  
  2. Multilevel marketing - Recommendations are some of the most powerful sales performers. We would encourage our users to recommend our app to their colleagues. Once the user recommends ten new users, they will gain one month of the premium tier.
  
  3. Advertising – To reach many schoolers we will use social media apps to advertise our product since majority of them are youth and spend most of their time using phones. One of the effective means we can also use is the use of the following media devices.  
Radio advertising – Since radio is one of the most used media of communication, we are going to commercially do short radio adverts, with appropriate information. To make it effective we will use the most listened radio station by most youths both internationally and locally radio stations.

  4. We will partner with organizations that offer scholarship. These scholarships from established organizations will be listed in our premium tier where students can access them.
 
 ## Additional Information:
 
  Udhamini proprietary database contains legitimate scholarships scraped and submitted by the scholarship providers themselves. A dedicated team vets, reviews, updates and adds scholarships to our database daily. If a scholarship is discontinued, we make sure to remove it from our database. Many sites rent an outdated list of scholarships with little information or offer scholarships that are highly promotional in nature.

  
