## How to edit yourself or add someone in people
- go to the yml file: `_data/people.yml`
- find your corresponding yml entries and edit
- or you can create a new yml entry, just look at the examples
- for the time being, don't add anything in `bio` subentry, this will break the vertical justification. I am not comfortable with CSS 🥲
- You can also add any other people as grad, undergrad, staff, alumni, or postdoc. Just follow examples in the yml files

## How to add a new publication
- go to the javascript file: ```js/data.js```
- in the ```dataset``` array variable, you just add a new array element
- this new array element should have the attributes just like the other array elements in the `dataset` array

## How to add a new research description
- go to the folder: `_projects`
- create a new markdown file, make sure the name is unique and does not conflict with other filenames in the directory
- put the contents in your new markdown file, there is one existing markdown file: `CTI-project.md` which will provide you the template. Just copy-paste the content of `CTI-project.md`file into your new file and edit accordingly.

## How to add a new photo in the gallery
- go to the folder: `_pictures`
- create a new markdown file, make sure the name is unique and does not conflict with other filenames in the directory
- put the contents in your new markdown file, there are few existing markdown file, such as: `2019-12-01.md` which will provide you the template. Just copy-paste the content of `2019-12-01.md`file into your new file and edit accordingly.

## How to add a new posts in the news
- go to the folder: `_posts`
- create a new markdown file, make sure the name is unique and does not conflict with other filenames in the directory
- put the contents in your new markdown file, there are few existing markdown file, such as: `2019-04-01-nasif-hotsos-2019.md` which will provide you the template. Just copy-paste the content of `2019-04-01-nasif-hotsos-2019.md`file into your new file and edit accordingly.