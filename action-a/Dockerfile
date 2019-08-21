FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello Beta-World"
LABEL "com.github.actions.description"="Testing out my first GitHub Action"
LABEL "com.github.actions.icon"="play-circle"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="https://github.com/cassshh/hello-github-actions"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Cassshh <octocat@github.com>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]