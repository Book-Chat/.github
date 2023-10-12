# Book Chat

## Description
Book clubs are often disorganized and difficult to find. Book Chat is an application that allows users to search for and join book clubs, create and manage book clubs and take notes on their reading. 

## Schema
<img width="1032" alt="Screenshot 2023-10-12 at 4 41 36 PM" src="https://github.com/Book-Chat/.github/assets/125829749/fce52052-7cf3-4d19-b1ff-55aff7d4251d">


## MVP Project Goals 

### Infrastructure
- Backend will be written with Ruby on Rails
- 

### Create basic webpage where users can view a book club and see what book is being read this month. 
 - The webpage will feature the title and other metadata about the book, which will require an API call to the GoodReads API.
 - Single page app, with picture of book, title and month.
 - Interface to Book Chat will consist of get/post/patch
 - Backend will need simple DB and get to GoodReads API
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
- 

### Private Book Clubs
- 

### Search Book Clubs
- No account can search and view book clubs

### GoodReads OAuth

### Book Notes
- Users can take notes on their reading. 

### Autogenerate meetings

## API Design 
*Include endpoints with example JSON responses along with notes on what the included information is.*

## Contributing 
*Include how to setup locally, run tests (separate out integration tests or not) and make PRs*
