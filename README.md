# Online Art Gallery Documentation

## The problem:

The problem we are aiming to solve with this website is the difficulty for new and experienced artists to gather attention towards their artworks and meet people with a similar or compatible taste in art.

## The solution/purpose:

Our idea is for an Online art gallery where artists and art enthusiasts can gather to show off their work, gain some attention towards it, and share their opinions with other like-minded people. This web application will attempt to help talented artists, no matter their circumstances, to get some publicity for their hard work. The site will also serve as a supportive place for new artists to show off their artistic projects and learn, gather inspiration from, and connect with others working in similar mediums. We believe this type of website will also have a number of transferable skills for common web development projects e.g. blogs, portfolio sites, etc.

## Functionality/features:

### Artists:

- Can create/delete an account
  - can upload their artworks to be displayed
  - can add a title
  - description/artist-statement
  - genre
  - medium
- Can create/update/delete content related to an artist profile with information about themselves and their practice
- Can view other artists profiles
  - sort by name, categories such as art-genre, medium, etc
- Can view all comments and report inappropriate comments on their own artworks
- Can view/create/update/delete comments they made on others artworks

### Art-lovers:

- Can create/delete an account
- Can view Artwork uploaded by Artists
  - Sort by name, categories such as art-genre, medium, etc
- Can create/update/delete comment on pieces of art
- Can view all comments and report inappropriate comments on pieces of art
- Can view all comments made by themselves

### Admins:

- Can view all login users' artworks or comments
- Can delete artworks not suitable for the website
- Can delete Artist accounts not suitable for the website
- Can delete comments not suitable for the website

---

## User Persona:

### Experienced Artist

**Blair**

**Bio**: Blair is a 50-year-old accomplished artist based in Sydney, Australia. With over three decades of experience in the art world, he has exhibited his sculptures in renowned galleries across the country. Blair is known for his mastery in capturing the essence of Australian wildlife through intricate metalwork and stone sculptures.
Blair's creations mirror the fluidity of movement in Australian wildlife. Beyond the art studio, he immerses himself in nature, exploring the surrounding national parks, capturing candid moments with his camera, and finding inspiration in the play of light on diverse landscapes. An advocate for environmental consciousness, Blair incorporates sustainable materials into his sculptures, reflecting his commitment to preserving the natural world.

**Goals:**

- **Exhibition Opportunities:** Blair is seeking new opportunities to exhibit his work, aiming to connect with a broader audience and continue his legacy in the Australian art scene.
- **Mentoring:** Passionate about passing on his knowledge, Blair is interested in mentoring emerging artists, sharing his experiences, and contributing to the growth of the next generation of Australian artists.
- **Networking:** Blair aims to expand his network within the Australian art scene, connecting with fellow artists, curators, and art enthusiasts.

**Challenges:**

- **Digital Transition:** While accomplished in traditional art practices, Blair is navigating the digital landscape and seeks a platform that respects his established artistic identity.

**User Stories:**

Blair wants to:

- Easily upload and showcase the latest sculptures, allowing to effortlessly upload high-quality images of the latest sculptures, providing a visually appealing and professional display on his artist profile.
- Receive notifications when someone leaves feedback on his artwork, that way his can engage with his audience.
- Mentor emerging artists and share experiences, allowing to connect with and provide guidance to emerging artists, fostering a supportive environment within the Australian art community.

### Emerging Artist

**Nicola**

**Bio:** Nicola, a 28-year-old emerging artist, calls Melbourne, her creative haven. Recently graduated from a local art school, Emma is passionate about exploring the dynamic relationship between urban landscapes and technology in her artwork. Her journey as an artist is marked by a commitment to pushing the boundaries of traditional artistic expression. Nicola finds inspiration in literature, exploring a spectrum of genres. Actively involved in the local art community, she attends events, fostering connections and drawing on the vibrancy of Melbourne's artistic scene. Nicola also enjoys occasional nature retreats, offering a contrast to her urban focus.

**Goals:**

- **Exposure:** Nicola seeks a platform that allows her to showcase her distinctive perspective and gain exposure within the diverse art community.
- **Feedback**: Nicola is eager to join a community where she can engage with experienced artists, receiving constructive critiques that contribute to her artistic growth.
- **Sales Opportunities**: While Nicola primarily focuses on expressing herself through art, she is open to the possibility of selling her creations to sustain her artistic endeavours.

**Challenges:**

- **Navigating the Art Scene:** Being a recent graduate, Nicola faces the challenge of navigating the vibrant art scene. She is enthusiastic about connecting with local artists, galleries, and art events to establish her presence.

**User Stories:**

Nicola wants to:

- Participate in virtual exhibitions that align with my digital art style giving the opportunity to submit digital artworks for consideration in virtual exhibitions and connecting with a diverse online audience.
- Access to analytics tools on the platform, offering insights into the performance of the digital artworks, including views, likes, and comments.
- Discover local art events and cultural activities, gallery openings, and cultural activities to enhance her engagement with the arts scene.

### Unintentional Visitor

**Emily**

**Bio**:
Emily, a 30-year-old visitor, stumbled upon an art gallery website by chance. Coming from a small town in the Australia, she works as a high school teacher and has never delved into the art world beyond admiring her students' creations. Despite her lack of artistic knowledge, Emily has always been fascinated by the various forms of expression and seeks to explore this newfound interest.

**Goals**:

- **Learning**: She hopes to understand art better, looking for a platform that helps explain and appreciate artworks.
- **Engagement**: Emily wishes to engage with the art community, connect with artists, and learn from their experiences to broaden her perspective.

**Challenges:**

- **Limited Art Knowledge:** Emily lacks formal education or exposure to art, which makes navigating the art world intimidating and overwhelming.
- **Understanding Art Terminology:** She finds it challenging to grasp the technical language used in art descriptions.
- **Identifying Personal Preferences:** Emily struggles to identify her preferences in art styles, mediums, or genres due to her limited exposure.

**User Stories:**

Emily wants to:

- Explore beginner-friendly exhibitions that introduce different art styles, providing explanations in simple terms.
- Engage in interactive features or forums where she can ask questions and receive explanations from artists or knowledgeable individuals in a welcoming environment.

## Application Architecture Diagram

## Tech Stack:

We decided on the MERN tech stack for this project, choosing MongoDB for the database, ExpressJS and NodeJS were selected for the back-end server and the front-end web client is handled by React. The use of MERN stack allows for flexible, non-repetitive and scalable full-stack design.

### Libraries:

- JWT:
- Bcrypt:
- Dotenv:
- Cors:

#### Front End:

- HTML:
- CSS:
- JavaScript:
- APIs:
- React-router-dom:
- React-bootstrap:

#### Back End:

- Express:
- Mongoose:

---

## Trello Board:

#### [Trello Link](https://trello.com/b/v5aGv47r/online-art-gallery)

![pic1](./docs/Trello%201.png)
