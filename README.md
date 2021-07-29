# codewestbrook

## Overiew of Project: 

The idea for this project started back in October of 2020. Myself and a group of friends who all go to the same gym (Crossfit Covalence) wanted a way to see the workout for the next day before the viewable time. Currently, the gym software (Wodify) used at our gym limits the viewing of the next day's workout till 10PM the day prior. You also can not view multiple days in advance. In an effort to solve this, I had an idea to create an Alexa app to pass through the required information into the Wodify API and Alexa would read off what the workout was. Clearly I was reaching for the stars- but it was the birth of this project. You will also note the "Test" hyperlink at the bottom of the page which will serve as the static page for the Alexa Dream project (yet to be completed).

## Front-End Web Development Features Used:


#Media Queries: 

1)
@media screen and (min-width: 750px){
    #WODcontent{
        width: 60%;
        padding:25px;
    }
}
2)
@media screen and (min-width: 1200px){
    #WODcontent{
        width: 80%;
        padding:25px;
    }
}

3) 

@media screen and (min-width: 750px){
    ul {
        display: flex;
        list-style-type: none;
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: #246;
        flex-direction: row;
        align-items: stretch;
      }
    }


#CSS:

1. Flex Box Menu Navigation
2. Hamburger menu- transforms to row menu on media query

#JS:
1. Jquery call 
2. Api Call to external source
3. Calendar Creation
4. Variable stores Calendar date
5. View workout button iniates Script over again.


#Note
Still actively working on Other tabs of the Website. Website was built for a friend group to see workouts in advance and meet CodeLouisville Requirements. 