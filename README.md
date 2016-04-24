Instructions:

Blacklist.json - completely blacklists a container / plugin
format:
[
  {
    "reponame |url to plugin": "Reasoning",
    "2nd repo name | url to plugin": "Reasoning"
  }
]
  
Moderator.json - Adds a moderator comment to a container / plugin.
format: Same as blacklist.json

Versions.json - Moderator override on compatible os versions for a plugin / container
format:
{
  "repo name | url to plugin":
  {
    "MinVer": "x.y.z",
    "MaxVer": "a.b.c"
  },
  {
    and so on
  }
}
  
  Note that both MinVer and MaxVer do not have to be present
