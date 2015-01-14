# my personal bash configuration
- clone the repository in your home directory
- create simbolick links to the commands directory
'for file in ${ZDOTDIR:-$HOME}/.bash/commands/*; do
  ln -s "$file" "${ZDOTDIR:-$HOME}/bin/${file:t}"
done'


