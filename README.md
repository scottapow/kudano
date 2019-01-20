# kudano
A Slack service to give valuable kudos (plural) to others

## Service Components and Ideals

The name kudano is greek for "to give hono(u)r/praise." A kudos (singular) is said praise.

### **Ideals**
- Hostable and Open Source
- Easy enough for non-technical groups to use/host
- Simple syntax for give a kudos

### **Components**
- API
   - GraphQL (choosing this because I'd like to learn it, not because it's the easiest or best choice)
   - All POST/PATCH etc. with be whitelisted to the slack host.
   - GETs will be whitelisted to the front-end host and slack.
- Front End
   - An easy place to claim rewards, see a history of kudos, and rank oneself.
   - Simple.
   - Gatsby/TS/React
- Slack
   - obv
   - Commands and params to follow
   - Settings to follow

## Usage

### **Slack**

Typing `/kudos [0-99] @username message here`:
1. adds the amount specified of kudos to the user specified.
   - If 0 is specified or the user has met their allowance, a different message is displayed.
1. subtracts from the daily/weekly allowance of the user giving the kudos if an allowance has been set.
1. Displays the kudos message in the set channel.


## Stages of Development
