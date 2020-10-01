# quiz js - Question
### 質問の内容↓   
1. localstrageに値が保存されない
2. HTMLに配列の要素を表示うまくできない


【Javascript】
```javascript 
const localsetUp = () => {
    const IsOutput = document.getElementById("js-local");
    let today = new Date();
    localStorage.setItem('history',point);
    const value = localStorage.getItem('history');
    const Array = [];
    Array.push({time:today.getFullYear() + ':' + (today.getMonth() + 1 ) + ':' + today.getDate(), point:value})
    const list = Array.map(obj => obj);
    console.log(list)
}
localsetUp();
```