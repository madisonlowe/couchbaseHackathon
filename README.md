# Couchbase Hackathon

This project was built during a day-long hackathon in August 2022 at the Manchester Couchbase offices, with [School of Code](https://github.com/SchoolOfCode)! 

Our brief was to create an app which would help to solve a real world problem: the only requirement was that we used Couchbase as our database provider. Prior to this hackathon, we had only encountered Couchbase in passing, and the majority of our database experience involved Express and PostgreSQL. Luckily, we had a member of the Couchbase team with us to assist!

We decided to make an app to track fires in the moors. There is a growing impact from things like BBQ fires and global warming upon the ecology of such areas. We hoped our app would help to track trends and allow fires to be tackled in a timely manner. Additionally, due to the malleability of non-relational databases, in future, the app might be able to track and record other kinds of ecological disasters which are increasing in moorland areas, like flash floods.

It was great to finally meet some fellow bootcampers in person, and to get to build and learn around other developers. Our work on this app paid off, as we were selected as the hackathon winners! There's still more to add, edit and improve on the app, but I had a great time coding with [@rachelalk](https://github.com/rachelalk) - and Ben at the office - and look forward to the next hackathon!

## Installation & Running

Start by cloning down this repository onto your local machine.

```
git clone https://github.com/madisonlowe/couchbaseHackathon.git
```

You'll be able to find the front-end code in the `Frontend` directory. It's written in React.

You'll be able to find the back-end code in the `Backend` directory. It's built using Couchbase, Node.js, and Express.

Change directory into `Frontend` and run `npm i` to install the front-end dependencies.

Then, change directory into `Backend` and run `npm i` to install the back-end dependencies.

You'll have to set up your own `.env` file at root level in the back-end directory in order to connect to Couchbase.

You'll be able to get your credentials from your Couchbase account. You can sign up for a free trial to try Couchbase out!

For this project currently, you'll need to add in your `clusterConnStr`, `username`, `password`, and `bucketName`.

Once you've got your `.env` set up, open a split terminal, and run the front and back-ends.

Run the back-end with:

```
npm start
```

Run the front-end with:

```
npm start
```

## Roadmap

In future, it'd be great to expand on the functionality of this project, and experiment more with the potential of non-relational databases. I'd also love to do some more work on the UI and front-end input handling. As Couchbase requires an active paid subscription to use their services - which I do not currently have - this project unfortunately cannot currently be demoed in its completed form. Excited for that to change in future!
