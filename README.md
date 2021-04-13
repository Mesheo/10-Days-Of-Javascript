# Why 10 days?
<p>
 Even tho I believe constancy beats intensity everytime, I also feel that us, progammers, get stuck if things doesnt have a well described scope. So i will give me 10 days of learning javascript to get excited knowing exactly where this project gonna end, and i hope to learn a lot in the process 
</p>

# Description
<p>
The repo files will be very similar and simple, I'm using <a href="https://www.hackerrank.com">Hackerrank</a>  and <a href="https://www.w3resource.com/">w3resource</a> to get the exercises. Also searching all around to get started with github stuff like README file and so on. On the chapter below I will document what I learned each day
</p>

# 📌 Days documentation

* [Day 1](#day-1%EF%B8%8F⃣)
* [Day 2](#day-2%EF%B8%8F)
* [Day 3](#day-3%EF%B8%8F⃣)
* [Day 4](#day-4%EF%B8%8F⃣)
* [Day 5](#day-5%EF%B8%8F⃣)
* [Day 6](#day-6%EF%B8%8F⃣)
* [Day 7](#day-7%EF%B8%8F⃣)
* [Day 8](#day-8%EF%B8%8F⃣)
* [Day 9](#day-9%EF%B8%8F⃣)
* [Day 10](#day-)

# Day 1️⃣
Started to get familiar with git CLI for uploading/manipulating repositories and understanding how the markdown language is used for making a nice Readme file.
<br>
The code of the day was about manipulating strings with loops and looked like this

```js
function vowelsAndConsonants(s) {
    let vowels = [];
    let consonants = [];
    
    for (var i =0; i < s.length; i++){
        if (['a', 'e', 'i', 'o', 'u'].includes(s[i])){
            vowels.push(s[i]);
        }
        else {
            consonants.push(s[i]);            
        }
    }
    console.log(vowels);
    console.log(consonants);
}
```
The logical part wasn't new to be, but i learn about important string methods as 

* includes() 
* charAt() 
* search()

 The most valueble part was reading about how to make an organized Readme file and expose your code to the world, this article helped and is still helping a lot: 
<a href="https://meakaakka.medium.com/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3"> A Beginners Guide to writing a Kickass README ✍ </a>

# Day 2️
I learned new string methods, as
* .split()
* .reverse()
* .join()

and also started to make error treatments with 
* try
* catch
* finally

<p>the code of the day was about comparison with numbers inside an array and looked like this</p>

```js
function getSecondLargest(nums) {
    // declara as variaveis que iremos atualizar durante a funcao
    let largestNumber = 0;
    let secondLargest = 0;
    // percorre os numeros do array nums para achar a maior variavel, atualizando largestNumber a cada interacao 
    for (var num in nums){
        if (largestNumber < nums[num]){
            largestNumber = nums[num];
        }
    }
    // agora com o maior valor definido fazemos a mesma varredura para encontrar o segundo maior valor
    for (var num in nums){
        if (secondLargest < nums[num] && nums[num] < largestNumber){
            secondLargest = nums[num];
        }
    }
    return secondLargest;
}

function main() {
    var nums = [1, 2, 4, 5];    
    console.log('o segundo maior número é: ', getSecondLargest(nums));
}

main()
```
Sometimes i got trouble with the different varible declarations we have inside javascript (let, var or const) and this article helped a lot: <a href='https://ui.dev/var-let-const/'> var vs let vs const in JavaScript  </a>

# Day 3️⃣
I improved my knowledge about errors with throw statement, and this article inside w3schools helped a lot: <a href="https://www.w3schools.com/js/js_errors.asp"> JavaScript Errors - Throw and Try to Catch </a>

To make the long history short we can say that 
* The `try` statement lets you test a block of code for errors.
* The `catch` statement lets you handle the error.
* The `throw`statement lets you create custom errors.
* The `finally` statement lets you execute code, after try and catch, regardless of the result.



# Day 4️⃣
This project was made using the follow technologies:
# Day 5️⃣
This project was made using the follow technologies:
# Day 6️⃣
This project was made using the follow technologies:
# Day 7️⃣
<p>asdasdas</p>
# Day 8️⃣
adadasda
# Day 9️⃣
dasda
# Day 🔟
