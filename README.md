# JokerBot
A Discord bot "Joker", completely built upon TypeScript

## COMING SOON
This bot is probably going to use [discord.js](https://discord.js.org/) framework,
though would like to avoid it in favour of a better JS/TS framework (one is in a concept,
it's called [PrismaCord](https://github.com/NorteX-dev/PrismaCord), though it's currently
stalled - lack of people willing to contribute). It will fully support slash commands,
interactions, and (if possible) also integration of Discord's Automod and Customization
API in future. Stay in touch on my [Twitter](https://www.twitter.com/TheCZghost) or join
my [development Discord server](https://discord.gg/YcDkrFU) and subscribe for updates.

## Roadmap
My vision on building this bot isn't clearly defined, I'm coming up with ideas on what
to do as things go, but the general idea is to make the alpha versions go out as soon as
humanly possible, with the most important features being released first, and less important
added later. Features I want to include (sorted from more to less important) are as follows:

1. **Moderation tools:** Commands for moderation purposes (kick, ban, mute, purge, warn, etc.).
   I also want to include some mass moderation tools, such as mass banning in case of a raid
   happening. Something most commonly used moderation bots don't have.
1. **Admin and maintenance tools:** Tools that allow you to make massive changes to your server,
   such as theme switching (for things like Pride month, etc. - changes your server icon, banner,
   etc.), or maintenance mode for example (where the bot restricts the server into a single
   channel where people can talk while the server is locked down).
1. **General public utilities:** Utilities like weather API, Google (using LMGTFY API), shards
   info, stats tracker for the server, bot's stats, etc.
1. **Entertainment:** Since this bot isn't intended to play music or engage in other voice
   activities, all entertainment features are gonna be text based. Features like cat gifs randomizer,
   or any other pet gifs randomizer, stuff like 8ball (magic quest tool), leveling system with
   a leaderboard, etc.
1. **Web panel backend:** This is a bit late plan, and it highly depends on the bot's success, but
   I'm of course aiming for user convenience for all the settings. Server owners and administrators
   with the "MANAGE_GUILD" permission will have access to the bot's dashboard to tweak the server's
   settings. Right now I have no idea which panel framework I'd be using for this, but every other
   major Discord bot seems to have one, so why not? This is also where I'd be looking into creating
   custom slash commands per guild, so server owners could potentially customize the bot to their
   liking. Obviously the options will be somewhat limited, but not too limiting. A nice task building
   API would be good, where server owners would build commands using blocks that represent individual
   tasks to perform said command - queries, data processing and actions.

Of course if something else happens to strike my mind, I'll fill it in.
