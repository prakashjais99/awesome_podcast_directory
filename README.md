# awesome_podcast_directory
Aim of this repository is to build directory to find list of all available podcast shows on internet. 
So that any one can use it to build podcast app

# Giude lines for submitting a podcast feed to list
Create a json file with name equal to MD5.hexdigest({feed_url}) 
Content will be like 
{
    title: #title of show
    feed_url: #RSS url for the show
}

# For example 
Ted-Ed show
{
    "title": "TED-Ed: Lessons Worth Sharing",
    "feed_url": "http://feeds.feedburner.com/Ted-edPodcast"
}
File name will be MD5.hexdigest("http://feeds.feedburner.com/Ted-edPodcast") = 2c6a6f9d4c2a824c5b6be973ef3e863a
So file name will be 2c6a6f9d4c2a824c5b6be973ef3e863a.json

Use https://cryptii.com/pipes/md5-hash to get md5 value for url

# Last step
Put file into index folder and to a pull request

# Note
First generate  md5 value for url and search for string in index folder to find if some one has already submmited.


