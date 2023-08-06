Adding Prefix to filename:
for /f "tokens=*" %a in ('dir /b') do ren "%a" "DivakarUpadhyay_%a"