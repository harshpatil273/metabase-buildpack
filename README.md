Heroku Buildpack for Metabase : https://www.metabase.com/releases/Metabase-0.51.4

Add the following to your app.json:

"buildpacks": [
  {
    "url": "https://github.com/metabase/metabase-buildpack"
  }
]
