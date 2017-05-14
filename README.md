# Welcome to Tree Identifier!

In this project we explored machine learning for the first time and set ourselves the task to build a Tree Identifier. Our plan was to use Tensorflow to train the computer on 55,000 images of leaves, so that we could upload an image of a leaf and the computer would give us a prediction of which tree it came from as well as the prediction accuracy.

As part of this project, we built a simple web application in rails where users could upload the leaf image.

### Technologies:
- Ruby on Rails (version 5.1)
- HTML/CSS
- Databases (postgresql)

### Key features:
- Navigate to homepage
- Click on 'Upload photo'
- The computer will display the image and a prediction of a which tree the leaf came from (the machine learning part was later implemented in a different repository - User: nazwhale, Repository: tree-spotter).

### Deployment instructions:
1. Navigate to your projects directory
2. Run ```git clone https://github.com/connie-reinholdsson/tree-identifier.git```
3. Run ```cd tree-identifier```
4. Run ```rake db:migrate``` to create the databases
5. Run `bin/rails s`
6. Navigate to the webpage 'localhost:3000/photos'
7. Follow the instructions to use the application.

Enjoy!
