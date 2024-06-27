# projects
{
  "description": "I created this Gist with cURL!",
  "public": true,
  "files": {
    "success.txt": {
      "content": "Yay, cURL!"
    }
  }
}
curl -iX POST --data "@curl.json" https://api.github.com/gists
curl --user "YOUR_USERNAME:$PAT" --data @curl.json https://api.github.com/gists 
