# Phase 3 Syllabus: Flex Program, 60 Week Pace

## Learning Objectives

Welcome to Phase 3! At this point in the program, you've mastered the frontend:
you've gained proficiency in one language, JavaScript, and can use React to make
single-page applications that access data from an API (either on a server that
someone else runs, or on your own `json-server`). You can officially call
yourself a frontend developer! 🎉

By now, you've likely felt the limitation of what you can build without having a
real backend. Fear not! This is the point in the program when that all changes,
and you become **full-stack** developers.

In this phase, you'll learn a new language, **Ruby**, which has some
similarities to JavaScript as well as its own set of unique features that make
it a much beloved language. You'll also learn how to use Ruby to interact with a
**SQL database** where you can control how data is persisted. With those tools,
you'll be able to build out your very own simple backend **API** so that your
next project can take advantage of all the benefits of full-stack development.

By the end of the phase, you will be able to:

- Understand the fundamentals of Ruby as a language, including principles of
  object-oriented programming
- Understand the characteristics of a relational database
- Perform CRUD (Create Read Update Delete) actions with a database via an
  Object-Relational Mapper
- Design an API to handle CRUD actions
- Communicate with an API using different HTTP verbs

Use the schedule below to make sure you're working through the material at
the right pace. The lessons marked with a ⭐️ are **milestones** that are useful
to check your understanding of the material you've learned. If you feel you're
falling behind, make sure to communicate with your instructor.

## Week 25 - 27

This week is all about learning the fundamentals of Ruby as a language.
Transitioning from one language to another is an important skill to have as a
developer (it's entirely possible your first job after Flatiron will require you
to learn a new language as well), so use this time to get to know and love Ruby.

You should be familiar with all the concepts from this week after having seen
them in JavaScript, so focus on the **syntax** and what makes Ruby unique.

After learning the basics of the language, it's time to learn Object-Oriented
Ruby. At its core, Ruby is a language for **object-oriented programming**.
You've seen some concepts related to object orientation in Phase 1 in
JavaScript; in this phase, you'll explore those concepts in more depth. You also
may find that Ruby also makes writing object-oriented code more pleasant than
JavaScript.

Make sure to take your time with the concepts here, and ask for help if anything
isn't clear. Mastering Ruby means building a solid understanding of
object-oriented programming, so the concepts here are key to your ability to
gain proficiency in the material later in this phase and the next.

**Total Assignments: (50)**

- Ruby Fundamentals (11)
  - ⭐️ Ruby Fundamentals Quiz
- Ruby Fundamentals: Arrays and Hashes (8)
  - ⭐️ Arrays and Hashes Quiz
- (Optional) Additional Practice: Ruby Fundamentals (8)
- (Optional) Regex (4)
- Introduction to Object-Orientation in Ruby (14)
  - ⭐️ Object-Orientation Fundamentals Quiz
- Topics in OO - Self in Ruby (8)
  - ⭐️ Self Quiz
- Topics in OO - Class Variables and Methods in Ruby (9)
  - ⭐️ Class Variables and Methods Quiz
- (Optional) Additional Practice: OO Ruby

## Week 28 - 30

This week, you'll wrap up the last couple topics on Object-Oriented Ruby, and
then get into the next big exciting topic on your programming journey: databases!

You'll start with the fundamentals of SQL to learn how **relational databases**
work and how to model complex data. Once you've learned a bit of SQL, next up is
connecting SQL to Ruby via an Object-Relational Mapper, or ORM. You'll start
by writing some basic features of an ORM by hand, and next week, you'll be introduced
to the Active Record library to make it easier to connect to a database and run SQL
using Ruby.

There's a lot of material here, so to help prioritize: the concepts in SQL and
Object-Relational Mapping (ORM) are important to know, but you won't end up
writing much SQL or ORM code yourself once you learn Active Record. If you find
those sections are slowing you down, talk with your instructor to help
prioritize, and focus on the readings over the labs from those sections.

**Total Assignments: (49)**

- Topics in OO - Object Inheritance in Ruby (9)
  - ⭐️ Object Inheritance Quiz
- Metaprogramming in Ruby (6)
  - ⭐️ Mass Assignment Quiz
- Configuring Ruby Applications (4)
- Getting Started with SQL (13)
  - ⭐️ SQL Quiz
- Table Relations in SQL (10)
  - ⭐️ Table Relations in SQL Quiz
- Object-Relational Mapping (7)
  - ⭐️ Object-Relational Mapping Quiz
- (Optional) Advanced ORM Methods (7)

## Week 31 - 33

This week is all about Active Record. You'll be using the Active Record library
as an ORM to connect your Ruby classes to a SQL database so you can create,
read, update and delete data. You'll also learn how to use Active Record to
connect between multiple classes and establish one-to-many and many-to-many
relationships.

The code challenge covers the material on Active Record, and it will also be an
important tool for Phase 4 and your final project, so make sure to spend a good
amount of time with this material.

**Note for students taking the code challenge**: the assessment will cover all
the material before **Sinatra**. It's recommended that you take the code
challenge after completing the Active Record Associations section and working on
some Additional Practice exercises.

**Total Assignments: (24)**

- Using Active Record (13)
  - ⭐️ Using Active Record Quiz
- Active Record Associations (6)
  - ⭐️ Active Record Associations Quiz
- Additional Practice: Active Record (5)
  - ⭐️ Phase 3 Active Record Mock Code Challenge: Freebie Tracker
- (Optional) Getting Data from Remote Sources (5)
- (Optional) Scraping (3)

## Week 34 - 36

There's one last section left before project time: Sinatra! Sinatra is a great
tool for creating small web servers. You'll need Sinatra to set up the backend
for your project, so make sure to take some time with these labs before beginning
the project.

**Total Assignments: (11)**

- Web API Basics with Sinatra (11)
  - ⭐️ Sinatra React Lab: Chatterbox

Then, time has come for your first full-stack project! In this phase, you'll be
building out a React frontend application once more, but you'll also have
control over the backend by creating your own server using Rack that can handle
requests from the frontend; communicate with the database using Active Record;
and send a response in JSON for the frontend to handle.

Details for the project can be found in the Milestones module.
