## console.log("Greetings! I'm Jason! Stay a while and listen...")

### Software Engineer
### Languages:  
- JavaScript, Ruby, Python
### Frameworks/Libraries:  
- Next.js, React.js, Google Apps Script, Ruby on Rails, Puppeteer, Cheerio, Langchain, Streamlit
### Databases/Tools:  
- Postgres, APIs, Node/npm, Git, GitHub, CLI

### Projects I am working on:
- In my current job role, I spend a lot of time in Google Sheets Extensions - Apps Script.  I utilize the combination of spreadsheet data, Sheet/Excel formulas, and editor code to help optimize and automate business tasks for a privately owned entity.  Anything from compiling data for inventory control, internal tasking reminders (either onEdit following event or cron job), or providing data for external audit B2B (mainly carriers, or sales channels).
  
### About Me / Background
- I've been connected to tech ever since I was a kid.  Born in the early 80's, I was in the generation that saw the beginning of home PC - Tandy, IBM PC.  This shaped a lot of what I would experience and grow with, and is responsible for a lot of my hobbies, interests, and life lessons.  Some of these interests are still with me as an adult, and I've been able to share them with my family / kids.

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
