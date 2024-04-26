# sports-data-scrapes
a collecton of processes designed to scrape stats, scores, etc from various sports games off the web

## Plan
- [ ] Create a list of sites to scrape data from
  - [ ] barttorvik.com (college basketball)
- [ ] Figure out how these things should be run (docker container that runs cron jobs on repeat?)
  - consensus seems to be invoke docker exec command from host cron https://www.reddit.com/r/docker/comments/9511ks/how_should_i_setup_periodic_tasks_in_docker/
- [ ] start scraping data