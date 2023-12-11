# Book Chat

## Description
Book clubs are often disorganized and difficult to find. Book Chat is an application that allows users to easily create and manage book clubs and invite members. Check the future features section for upcoming application features. 

## Schema
<img width="1032" alt="Screenshot 2023-10-12 at 4 41 36 PM" src="https://github.com/Book-Chat/.github/assets/125829749/fce52052-7cf3-4d19-b1ff-55aff7d4251d">

*Removing rating, genres, pages, and summary fields from the Books table. This information will be acquired from Google Books API call.*

## MVP Project Goals 

### Infrastructure
- Backend will a RESTful API written with Ruby on Rails
- Frontend will be Ruby with Turboframes and Tailwind
- CircleCI for CI/CD
- Hosting with AWS

### Create basic webpage where users can view a book club and see what book is being read this month. 
 - The webpage will feature the title and other metadata about the book, which will require an API call to the Google Books API.
 - Single page app, with picture of book, title and month.
 - Interface to Book Chat will consist of get/post/patch
 - Backend will need simple DB and get to Google Books API
 - No user auth will be performed at this point.

### User Login 
- No account can see single page app
- Only admin can update book, month information and manage members.

### Create and Manage Book Clubs
- Users can create book clubs.
  - Book clubs will have a title, special interest(s), and genre(s).
- A book club created by a user is owned by the user.
- A user may be a member or owner of multiple book clubs.
- An owner of a book club can appoint other users as book club owners. (Other roles may reveal themselves as development continues).
- Owners can edit their own book club, but they cannot edit other book clubs.
- Site admins can view and edit any book club.
- Users can join any book club.
- Homepage is a list of all book clubs.

## Future Feature Ideas

### Book Club Message Boards
- Members of a book club can post chat messages in the book club message board.
- Only book club members can see book club message board posts.
- Message board history persists.
- Members can edit and delete their messages.
- Book club owners and site admins can delete messages.

### Book Club Chats
- Book club owners have the optino to create a new chat channel for each book read.
- Chat channels will allow users to reply in thread.
- Users can DM other book club members

### Private Book Clubs
- Book club owners can choose to make their book club discoverable for anyone to join or private so that members can only join by invitation.

### Search Book Clubs
- Users without an account can search and view book clubs.
- Users can search for book clubs based on location, books on the book list, genre(s) and special interest(s) (LGBTQ+, Women's club, etc.).

### GoodReads OAuth
- Users can sign in with GoodReads and import currently reading and other book list as well as submit and view their reviews.

### Google OAuth
- Users can sign in with Google and import Google Books lists as well as submit and view their reviews.

### Book Notes
- Users can take notes on their reading. 

### Autogenerate meetings
- Users can input a date, time and frequency of their book club meetings and select number of meetings to autogenerate.
- With meeting autogeneration, users can select how they want to pair a book from their book list with each meeting. Random, by rating, voting, etc.

## API Design 
*Include endpoints with example JSON responses along with notes on what the included information is.*

## Contributing 
*Include how to setup locally, run tests (separate out integration tests or not) and make PRs*
