# node-FirebaseAuthentication

* ?Anonymous status must be activated to sign up with Firebase Authentication.

```
_______________________________________________________
*app.js*

*****************"type": "module",**********************
import { fileURLToPath } from 'url';
const __filename = fileURLToPath(import.meta.url);
const __dirname = path.dirname(__filename);
********************************************************

app.use(express.static(path.join(__dirname, 'public/html')));
app.use(express.static(path.join(__dirname, 'public/css')));

app.get("/", (req, res) => {
    res.sendFile(path.join(__dirname,'public/html', 'login.html'));
})
_______________________________________________________
(public/html/login.html - public/css/bootstrap.min.css)
*login.html*

x <link href="../css/bootstrap.min.css" rel="stylesheet"> x
<link href="bootstrap.min.css" rel="stylesheet">
_________________________________________________________
```
