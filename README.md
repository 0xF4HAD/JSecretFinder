# JSecretFinder
Tool for discovering API keys & access tokens and sensitive data in js file

Usage
cat js.txt | while read url; do python3 JSecretFinder.py -i $url -o cli >> secret.txt ; done
