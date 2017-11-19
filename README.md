# node-express
node练习第三节
```javascript
app.get("/",(req,res)=>{
    console.log(`method:${req.method}`);
    console.log(req.params.name);//获取参数
    console.log(req.query.username); //获取url？后面的对象
})
```
```javascript
const bodyParser=require('body-parser')
app.use(bodyParser); //express中间件

app.use((err,req,res,next)=>{
 res.status(401)
})
```



