## console.log("Greetings! I'm Jason! Stay a while and listen...")

### I'm a Software Engineer / Full Stack Developer, and like a lot of coders I love the feeling of the puzzle coming together and that rush you get from that feature finally working.
### Languages:  
- Ruby, JavaScript, HTML, CSS, SQL
### Frameworks/Libraries:  
- Ruby on Rails, React.js, Bootstrap, Tailwind, Puppeteer, Cheerio
### Databases/Tools:  
- Postgres, APIs, Node/npm, Git, GitHub, CLI

### Projects I am working on:
- Magic the Gathering Deck / Collection Manager
- Magic the Gathering Webscraper
- HeroesApp. RESTful API for Heroes of the Storm team comps / player roles / character roles / tiers.

### Hobbies
- Music
- Magic: The Gathering
- Hearthstone
- Heroes of the Storm


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
