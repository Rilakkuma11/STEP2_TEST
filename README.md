# step2_test

mkdir step2_test
cd step2_test
git init
echo "GitHub">example.txt

git remote add origin https://github.com/your-username/step2_test.git
git add example.txt
git commit -m
git branch -M main
git push -u origin main

git checkout -b test
git push -u origin test

echo "This is a pull request test.">>example.txt
git add example.txt
git commit -m "プルリクテクト”

git push origin test
