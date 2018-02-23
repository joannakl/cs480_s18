# Course website for CS480, Section 10 (Spring 2018)
---
Currently under class exercise experiment. 
Bugs to be fixed by students. 

## Setup
### MacOS
```
brew update
brew install ruby
gem install jekyll bundler
```

### Linux
```
sudo apt-get update
sudo apt-get install ruby ruby-dev make gcc
gem install jekyll bundler
```
### Windows
TBA.

## Running
In `_config.yml`, change this line: `baseurl: ""` 
```
git clone https://github.com/joannakl/cs480_s18.git
cd cs480_s18
jekyll serve
```
Navigate to http://127.0.0.1:4000/