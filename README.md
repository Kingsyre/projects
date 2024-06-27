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
