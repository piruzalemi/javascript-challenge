# javascript-challenge
Using the UFO dataset provided in the form of an array of JavaScript objects, this Alemi repository appends a table to my web page and then adds new rows of data for each UFO sighting.

# Level 1: Automatic Table and Date Search

I made sure I have a column for date/time, city, state, country, shape, and comment at the very least.

Used a date form in my HTML document and wrote an Alemi JavaScript code that will listen for events and search through the date/time column to find rows that match any users input.

# Level 2: Multiple Search Categories

In part II. 

I Used multiple input tags and/or select dropdowns. I wrote JavaScript code so the user can set multiple filters and search for UFO sightings using the following criteria based on the table columns:

date/time
city
state
country
shape

Piruz Alemi Feb 5th, 2020

ps. 3 Records from Input data is provided as a sample of data used:

var data = [{
    datetime: "1/1/2010",
    city: "benton",
    state: "ar",
    country: "us",
    shape: "circle",
    durationMinutes: "5 mins.",
    comments: "4 bright green circles high in the sky going in circles then one bright green light at my front door."
  },
  {
    datetime: "1/1/2010",
    city: "bonita",
    state: "ca",
    country: "us",
    shape: "light",
    durationMinutes: "13 minutes",
    comments: "Three bright red lights witnessed floating stationary over San Diego New Years Day 2010"
  },
  {
    datetime: "1/1/2010",
    city: "el cajon",
    state: "ca",
    country: "us",
    shape: "triangle",
    durationMinutes: "6 minutes",
    comments: "On New Years Eve I went outside to hear the celebration and fireworks in my neighbor hood. And noticed 3 red lights above my house and"
  },


