Cards. Cards Everywhere
-------------------------


Bourbon has super sweet cards, but it's a bit hard to use if you're not familiar
with the bourbon/neat/refills stack.

Here's an example of a working system.

To get here:

1. gem install bourbon, refills, bitters, and neat
2. Go to app/assets/stylesheets
3. `rails g bourbon install`
3. `rails g bitters install`
3. `rails g neat install`
3. `rails generate refills:import cards'


This will create the files herein. (Besides a page to render the cards partial)

![img](http://i.imgur.com/Chp0lMu.png)
