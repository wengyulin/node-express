# node-express
node练习第三节
```javascript
app.get("/",(req,res)=>{
    console.log(`method:${req.method}`);
    console.log(req.query.username); //获取url？后面的对象
})
```
