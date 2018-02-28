# MEVN-posts
A fullstack posts panel boilerplate with Mongo, ExpressJS, VueJS and NodeJS.
Includes WYSIWYG editor [vue2-editor](https://www.npmjs.com/package/vue2-editor)
Originally a fork of [anaida07 MEVN-boilerplate](https://github.com/anaida07/MEVN-boilerplate)

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOOiKh1Xk5RDZFKPkVXYfi8U-t2cuotiAOR7G_7w_HWXfV02TMnd9wnVM" height="50" /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://i.cloudup.com/zfY6lL7eFa-3000x3000.png" height="50" /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://vuejs.org/images/logo.png" height="50" />  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Node.js_logo_2015.svg" height="50" /> 

A skeleton generated with MEVN stack technologies which can be used as a boilerplate for anyone who is starting out. It contains a client template(**VueJS**) and a server template(**NodeJS**, **ExpressJS**) and a connection between them via an API layer.


## Setup Development Machine
1. Clone the repo `git clone git@github.com:marcelozarate/MEVN-posts.git`

2. `cd MEVN-posts`

3. Open client
```
cd client
npm install
npm run dev
```

4. Make sure Mongo daemon is running
```
sudo service mongod start
```

5. Open server
```
cd server
npm install
npm start
```

6. Open `http://localhost:8080/posts` in browser