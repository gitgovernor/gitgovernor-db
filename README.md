# gitgovernor-db
A Custom Database Backend for gitgovernor.
can be used as central issue tracking system standalone.


## Filestructure
can be user or organisation or repo we will add ext by type: user, org, repo, 
we split into 2 main folders
- credentials
  { username, tokens, platforms, description, id }
- local
  - path-to-seprated + custom seperator default (-) (/home/frank/workspace/github.com/frank-dspeed => home-frank-workspace-github.com-frank(-)dspeed )
- remote
  - domain/path => issues, commits. stars, type: user/org, organisations: [], followers: [], following: [],repos:[],projects/boards:[], pullrequests: []


