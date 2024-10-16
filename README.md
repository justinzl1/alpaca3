
# Team-24: Alpaca 3

[Demo Video](https://www.youtube.com/watch?v=DHfRfU3XUEo&ab_channel=FailArmy)</br>
[Devpost](devpost.com)

# Team Members
### Justin Lee
- [Github](https://github.com/justinzl1)
- [LinkedIn](https://www.linkedin.com/in/justinzl)
  
### Dheeraj Kallakuri
- [Github](https://github.com/dheerajkallakuri)
- [LinkedIn](https://www.linkedin.com/in/dheerajkallakuri/)

### Ramy Bagaghayou
- [Github](https://github.com/mcaramy)
- [LinkedIn](https://www.linkedin.com/in/rbabagha/)

### Umang Rajnikant Bid
- [Github](https://github.com/UmangBid)
- [LinkedIn](https://www.linkedin.com/in/umang-bid/)


# Info

[Our Slack](https://opportunity-hack.slack.com/app_redirect?channel=alpaca_3_laminal_works)</br>
[About Liminal Works](https://www.liminal-works.org/about)</br>

# Problem Statement

Liminal Works currently enlists the help of its volunteers to develop theories of change for grassroot activists and organizations. 
This task can be very time-consuming and subjective. Using AI to facilitate this process, the time spent developing theories
of change is significantly reduced, allowing for volunteers and employees to allocate their time to more important tasks.

# Introduction

Alpaca 3 is an AI model trained on data about theory of change (TOC), what makes a good TIC, and how to craft a TOC. Users are able to 
directly ask Alpaca 3 questions they have, or they can upload pdfs that the AI will scan and respond to. 



# How it works

The user writes text or uploads a pdf, and this input is then sent as a query to the API gpt that generates a response. 
The response is filtered through a database containing data about TOC. If the response relates to TOC, the AI response
is let through. If not, the AI responds with how the query is not relevant to TOC.

<img width="3136" alt="Flow Map" src="https://github.com/user-attachments/assets/52570d3a-185b-4f86-861a-5573b8be203b">



# Challenges we ran into

We had some difficulties determining what makes a good theory of change and how to develop one and how an AI would be able to determine this as well. 
The data provided to train the model was very limited, so we had to solve this problem by manually training our model with other resources. Our front-end
and back-end could have used more communication because system integration proved to be a challenge.



# Accomplishments we are proud of

System integration was an accomplishment we are proud of. It was difficult to get the front-end and back-end to work together seamlessly, but 
once we got it working, we were all relieved and happy.

# What we learned

It was some of our first times working with AI/machine learning and databses, and for one of us, it was our first time coding. We learned a lot about
creating programs with these features. The system uses multiple technologies in order to fulfill the problem statement. These technologies include, but not limited to :
1. MongoDB NoSQL Database
2. Natural Language Processing (NLP) and Artificial Intelligence (AI) techniques like Retrieval Augmented Generation (RAG) model
3. Open source python frontend framework like Streamlit
4. Web Scraping technologies and libraries like BeautifulSoup
   

