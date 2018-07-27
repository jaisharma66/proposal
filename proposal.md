# CSCI S-33a: Project Proposal
## Due: Friday, July 27 at 6pm

#### Your name

Jai Sharma

#### Your teaching fellow's name

David Nunez

#### Which language(s) will you use for your project?

JavaScript, Python, HTML

#### What will (likely) be the title of your project?

Lausanne Model United Nations Website for Student Connections

#### In just a sentence or two, summarize your project. (e.g. "A website that lets you check the weather in different cities.")

My website will be an app where users can check updates for the MUN club at my school. There will also be a messaging app within it
where users can ask questions about assignments and due dates.

#### Where will your project ultimately live? (e.g. within CS50 IDE, Heroku, AWS, some commerical web host...)

CS50 IDE

#### In a paragraph or more, detail your project. What will it do? What features will it have?

My project is a website that I will be designing for my MUN club at school. There will be a few main aspects of the website that I will
have. Firstly, the website will be a multipage application, with the pages being (subject to change) Home, Announcements, Resources, and Chat.
This will employ elements of both a multipage application and aysnchronous requests. The Home page will display main content and recent updates
while the announcements page will contain recent announcements that club members should know about. Furthermore, on this page, users will be
able to see a google calendar with important dates. This will be using the google calendar API key which I have acquired (free) credentials
for. Furthermore, everything will be dated so that users can jump to specific dates that they request. There are many ways I can implement this,
but I am thinking about either having a side bar where the users can jump to specific locations or by having a search bar where users can enter
a date and the program will jump to that location. A select box may also work.

The resources page will be quite simple, it will simply have links and descriptions to different resources that users can refer to.
For this section, if time allows, then I would like to use the google feed api to integrate news feeds to this part of the site.
It shouldn't be too difficult to implement the RSS feeds.

For the final part of the project, I will be adding a chat section that will be very similar to the chatterbox. The difference here will be
that this chatterbox will have the amount of people displayed in the chat. Furthemore, with my new knowledge on the chatterbox, I will have
much better implementation using Socket rooms to create the different channels. It will also support some extra features such as picture uploading
and private messaging if time allows.

<hr>

- In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

#### In a sentence or list, define a GOOD outcome for your project. What WILL you accomplish no matter what?

A good outcome for the project would be getting all 4 pages setup and having the APIs working as intended. The chat section working
as intended during project2 will be a goal to strive for as well. I want the chat to be seamless and have no bugs.

#### In a sentence or list, define a BETTER outcome for your project. What do you THINK you will accomplish in time?

A better outcome would be having the RSS feed API to work alongside having messaging being more robust with picture uploading and more being
available to the user. I believe that I should also be able to implement private messaging between users.

#### In a sentence or list, define a BEST outcome for your project. What do you HOPE you will accomplish in time?

The best outcome would be having every attribute implemented perfectly within the website. If I can accomplish everything above, then
I may attempt to implement some sort of login using flask login from project 1. This would be the goal that I would attempt if time permits.
I am, throughout the project, going to be styling, but only enough to make the website presentable. At this point, I would like to style the
website to look very nice if time allows.

#### In a paragraph or more, outline your next steps. What new skills do you need to acquire? What topics will you need to research?

The steps required to succeed in this projet will include learning to use and implement google's calendar and possibly RSS APIs.
Google has very good documentation for both APIs making this quite easy to do. Furthermore, I will have to learn how to use SocketIO
rooms to make new channels. This will be a change from what I did for project2 because my original implementation was quite poor. I will
also need to research how to do private messaging and how to make sure that a user cannot send a message until they have filled out all the
required credentials and such. The reserach will not be too much, but I will need lots of help from different resources for implementation methods
as I have often not done things in the most efficent manner in the past. My goal for this project is to make sure that everything operate correctly.
Below, I will outline some steps that I will take:

1) Setup the 4 pages
2) Configure APIs and the Resources and Announcements Pages
    a) Research APIs as needed and fully implement
    b) Style the 2 areas to be decent and not hinder users
3) Get basic chat settings working
    a) Display Name
    b) Channels using rooms
    c) Proper messaging
    d) Display number of users in a channel
---------------------------------------------------------------
4) Advanced chat settings working
    a) Private messaging
    b) Image uploading
    c) Proper chat design
---------------------------------------------------------------
5) Possible login using flask if time permits