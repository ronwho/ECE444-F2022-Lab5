# CARTE Education Pathways

## This is a clone of https://github.com/nelaturuk/education_pathways. 
## Ron Hu and Malhar Shah

## Activity 1
![Screenshot of Activity 1](/images/Activity1.jpg)

## Activity 2 to Activity 5:
```
Home Page
```
![Screenshot of Home Page](/images/Activity2.jpg)

```
Results Page – Form
```
![Screenshot of Results Page – Form](/images/Activity3.jpg)

```
Results Page – Results Table
```
![Screenshot of Results Page – Results Table](/images/Activity4.jpg)

## Activity 6
### User Story 3.1.2 from Milestone 3
![Screenshot of User Story 3.1.2](/images/Activity6-1.jpg)
![Screenshot of User Story 3.1.2](/images/Activity6-4.jpg)

### User Story 3.2.1 from Milestone 3
![Screenshot of User Story 3.2.1](/images/Activity6-2.jpg)
![Screenshot of User Story 3.1.2](/images/Activity6-5.jpg)

### User Story 3.3.1 from Milestone 3
![Screenshot of User Story 3.3.1](/images/Activity6-3.jpg)
![Screenshot of User Story 3.1.2](/images/Activity6-6.jpg)

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
