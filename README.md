# RABBIT

## APP DESCRIPTION:
Rabbit is a web-based platform where users can create and join online communities to share information and content on various topics. The platform allows users to submit posts, comment on others' posts, and vote on content, determining its popularity and visibility within the community. 

## DATA MODEL:

![image](https://user-images.githubusercontent.com/122382995/229201943-b411f917-017c-42be-9126-69fd74f330b3.png)

## COMPONENT TREE:

![image](https://user-images.githubusercontent.com/122382995/229196480-43192843-33e1-43fd-89a2-f6c57e37aa59.png)


## ROUTING TABLE:

| Route                | HTTP Method | DB Action | Description             |
| -----------          | ----------- | --------- | ----------------------- |
| /api/                | GET         | INDEX     | Indexes                 |
| /api/profile         | GET         | INDEX     | Indexes                 |
| /api/                | POST        | CREATE    | Create                  |
| /api/:user           | GET         | SHOW      | Show                    |
| /api/profile/:anime  | PUT         | UPDATE    | Update                  |
| /api/delete          | DELETE      | DELETE    | Delete                  |


## WIREFRAMES: 



## MVP:
### Planning <!-- omit in toc -->

- Have a thoroughly documented `Team Expectations` Google document / markdown file.
- Have a **thoroughly** developed, **beautiful** `README.md` file.
- Take time for each team member to discuss where they feel strongest and weakest, in terms of coding ability.
- Create a Whimsical document to convey the data flow with component hierarchy included.

### Collaboration <!-- omit in toc -->

- Contribute equally.
- Have a solid understanding of the _entire_ project. (Even the features implemented by other team members.)
- Take time to pair program with teammates to reinforce learning.
- Be prepared to explain sections of code that were written by teammates.

### Client (Front End) <!-- omit in toc -->

- Have a working, interactive **React** app, built using `npx create-react-app client`
  - Have at least 6 separate, rendered components in an organized and understandable React file structure.
  - Utilize functional and class React components appropriately.
  - Use _only_ React for DOM Manipulation.
- Consume data from your **API**, and render that data in your components.
- Utilize **React Router**, for client-side routing.
- Authentication!

### Server (Back End) <!-- omit in toc -->

- Have working generic controller actions for CRUD
- Authentication

### Styling <!-- omit in toc -->

- Be styled with CSS.
- Use flexbox (`display: flex`) or CSS Grid.
- Implement responsive design on 2 screen sizes (including desktop) using a media query (mobile).

### Linting <!-- omit in toc -->

- Indent properly.
- Utilize high-quality, semantic variable names and follow naming conventions.
- Remove unnecessary boilerplate React files and code.
- Remove all `console.log()`s and commented out code (functional notes/comments are okay).

### Deployment <!-- omit in toc -->

- Deploy the fully functional front-end via Vercel.
- Deploy the back-end via Vercel.
- Deploy the MongoDB database on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

### Procedural <!-- omit in toc -->

- Have _frequent_ commits from _every_ team member dating back to the _very beginning_ of the project. These commits should total to or exceed _50_.
- Use _effective_ and _safe_ branching and merging processes.

### MVP Components

- [] Navigation bar which has a homepage, profile page, and posts.
- [] Component that displays username, and points. Below the image, comment, and other users' comments are rendered. 
- [] Routes/links to the aforementioned components.

### POST MVP: 
- [] Search bar functionality is fleshed out.
- [] User comments on other users' reviews are implemented.

### GOALS:

- [] Day 1: Get the project off the ground: proposal, notion, repo, etc.
- [] Day 2: Authentication/flesh out backend.
- [] Day 3: Developing components (NavBar & Post).
- [] Day 4: Developing components (New Post & Edit/Delete).
- [] Day 5: Formatting CSS.
- [] Day 6: Formatting CSS (Cont.) & Post-MVP.
- [] Day 7: Finalizing details (Git, Github, Vercel).

### TEAM COLLABORATION DETAILS:

* Notion Board: https://kaput-freesia-a91.notion.site/Reddit-Clone-720f974111364060b32373cb3a0a40b5
* Team Expectations: https://docs.google.com/document/d/10Glqu3UixWdq_Wzdj7adVZXTC6UprzVKnIunb5wAe7k/edit?usp=sharing
