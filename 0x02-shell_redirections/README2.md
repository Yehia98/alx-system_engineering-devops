echo "Hello, World"
echo "\"(Ôo)'"
cat /etc/passwd
cat /etc/passwd /etc/hosts
tail -n 10 /etc/passwd
head -n 10 /etc/passwd
head -n 3 iacta | tail -n 1
ls -la > ls_cwd_content
tail -n 1 iacta >> iacta
find . -type f -name "*.js" -delete
find . -type d -not -name "." | wc -l
ls -t | head -n 10
sort | uniq -u
grep -i root /etc/passwd
grep -ci bin /etc/passwd
grep root -A 3 /etc/passwd
grep -v bin /etc/passwd
grep -i ^[a-z] /etc/ssh/sshd_config
