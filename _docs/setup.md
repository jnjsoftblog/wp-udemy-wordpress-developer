# 최초 생성(windows11)

## local sites

"""
name: wp-udemy-wordpress-developer
user: master.vw
password:
email: jnjsoft.blog@gmail.com
"""

## files

### folder.file 삭제, 복사

```sh
cd "C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public"
rmdir /s /q "wp-content\themes\twentytwentythree"
rmdir /s /q "wp-content\themes\twentytwentytwo"

copy "C:\Users\Jungsam\Local Sites\wp-class101-from-planning-to-launch\app\public\.gitignore" "C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public\.gitignore"

xcopy "C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public\_docs\*" "C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public\_docs\" /s /e /h /y
```

## vscode
### 작업영역에 폴더추가
C:\Users\jungsam\Local Sites\wp-udemy-wordpress-developer\app\public

### 수정

> `C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public\_docs\setup.md`

## github

```sh
cd "C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public"
github -e pushRepo -u jnjsoftblog -n wp-udemy-wordpress-developer -d "UDEMY Become a WordPress Developer: Unlocking Power With Code"
```