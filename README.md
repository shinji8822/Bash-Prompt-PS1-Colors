# Bash-Prompt-PS1-Colors

# We need to encapsulate with "\[ \]" to use in a prompt
BLUE1='\[\033[1;34m\]'
BLUE2='\[\033[34m\]'
GREEN1='\[\033[1;32m\]'
GREEN2='\[\033[32m\]'
CYAN1='\[\033[1;36m\]'
CYAN2='\[\033[36m\]'
RED1='\[\033[1;31m\]'
RED2='\[\033[31m\]'
PURPLE1='\[\033[1;35m\]'
PURPLE2='\[\033[35m\]'
BROWN1='\[\033[1;33m\]'
BROWN2='\[\033[33m\]'
GRIS1='\[\033[1;37m\]'
GRIS2='\[\033[37m\]'
YELLOW1='\[\033[1;33m\]'
YELLOW2='\[\033[33m\]'
WHITE='\[\033[1;37m\]'
NOCOLOUR='\[\033[0m\]'

# Don't forget to use double quotes "
PS1="$CYAN1\u@\h $GRIS2\w $YELLOW2>$PURPLE2>$RED1> $NOCOLOUR"
export PS1
