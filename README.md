- 👋 Hi, I’m @DucMinhNgo, my blog is (https://ducminhngo.github.io/ngominhduc.github.io/).
- 👀 I’m interested in Go, Python, Javascript.
- 🌱 I’m currently learning Google Cloud Platform, Ensemble learning.

curl -s "https://api.github.com/users/DucMinhNgo/repos?per_page=200" \
  | jq -r '.[].languages_url' \
  | xargs -I {} curl -s {} \
  | jq -s 'add | to_entries | sort_by(-.value)' \
  | jq -r '(["| Language | Bytes |","|---:|---:|"] | .[]), (.[] | "| \(.key) | \(.value) |")'



<p align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=DucMinhNgo&theme=nord_bright">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=DucMinhNgo&theme=nord_bright">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=DucMinhNgo&theme=nord_bright">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=DucMinhNgo&theme=nord_bright">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=DucMinhNgo&theme=nord_bright&utcOffset=+7">
</p>


