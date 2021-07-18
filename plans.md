# Roadmap (non-visual)

## V0
work command
- no flags, type work and then some text in quotes. text gets dropped into a file. with a timestamp and the directory called from (this may not actually be helpful but it might be)
- This will get stored as json...

## v1
- flags
    - j > reference to a jira ticket (maybe use some minimal validation)
    - f > reference to a file
    - s > reference to a website
    - b > reference to a billing task

## v2 
- b updates
    - make billing have some shortcuts or be aware of what projects exist
    - is this somehow a harvest integration, can this be done as a plugin so that other sources could be used
    
## v3
- start/stop/state
    - track when work starts be able to then track when it stops
    - be able to push that data to harvest (or another plugin) based on v2
    
## v4
- this is probably tighter jira integration 
  - see current work/ get links to current work
    
# Roadmap (visual)
## v0
- convert stored json to markdown or something else to be able to nicely look at, this file is maybe always overwritten, and definitely not the source of truth

# Roadmap (portability)
## v