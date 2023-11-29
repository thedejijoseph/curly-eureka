i'm taking the next steps with the [nashville](https://github.com/thedejijoseph/nashville) project. here's a breakdown of how i expect things to go

data source has been identified to be jiji classified ads.

I thought I'd have to write scripts to crawl their pages, but fortunately, they have a publicly accessible json api. i'll be pulling from that instead

next up

- [ ] use google sheets to breakdown the most important information needed for the project
- [ ] use a notepad or code, to map json objects to the required fields
- [ ] write script to call the apis and transfer said data into tables (csv rows and columns)
- [ ] write that data into a postgres database
- [ ] write script that pulls that data out and returns it several formats (json, csv) via code (i.e vis is done with python) and api (i.e vis is done via tableau, or public access is shared to data)
- [ ] begin visualisation

