## console.log("Greetings! I'm Jason! Stay a while and listen...")

### I'm a Software Engineer / Full Stack Developer, and like a lot of coders I love the feeling of the puzzle coming together and that rush you get from that feature finally working.
### Languages:  
- Ruby, JavaScript, HTML, CSS, SQL, PHP
### Frameworks/Libraries:  
- Ruby on Rails, React.js, Puppeteer, Cheerio, PHP/WordPress
### Databases/Tools:  
- Postgres, APIs, Node/npm, Git, GitHub, CLI

### Projects I am working on:
- Magic the Gathering Deck / Collection Manager
- Magic the Gathering Webscraper
- HeroesApp. RESTful API for Heroes of the Storm team comps / player roles / character roles / tiers.  OAuth ready.

### Hobbies
- Music
- Magic: The Gathering
- Hearthstone
- Heroes of the Storm

### About Me / Background
Before becoming a Software Developer / Engineer, I worked for a larger corporate Property and Casualty insurance carrier.  I wore many hats there, from Sales / Underwriting / Risk Assessment / Edit Error Guidance.  I developed a sales acumen there, and a true view of what UI / consumer friendliness really should be.  Previous to that I worked for a privately owned video game / collectible card game / pop culture store.  I wore many hats there as well, from front facing brick and mortar to e-commerce management / sales and development.  

```
const handleDestroyCard = (card) => {
    console.log("handleDestroyCard", card);
    axios.delete(`http://localhost:3000/cards/${card.id}.json`).then(() => {
      setCards(cards.filter((p) => p.id !== card.id));
      handleCloseCard();
    });
  };
```
The card id here should always point to Griselbrand...
