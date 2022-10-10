function spongeTalk(string){
  let strArr = string.toLowerCase().split('')
  let i = 0;
  while(i < strArr.length){
    let coin = Math.floor(Math.random() * 11);
    if (coin % 2 == 0){
      strArr[i] = strArr[i].toUpperCase()
    }
    i++;
  }
  let output = strArr.join('');
  console.log(output)
}

spongeTalk(`abcdefghijklmnopqrstuvwxyz`)
