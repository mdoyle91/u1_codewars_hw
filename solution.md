## Return Negative

```js
function makeNegative(num) {
    if (num > 0){
      return -num
    }
    if (num < 0){
      return num
    }
    else return 0
  }
  
  makeNegative()
```
<!-- Utilized Google to look up how to write return statements--followed AI //generated response in main search https://www.google.com/search?q=writing+return+statements+in+javascript&rlz=1C5CHFA_enUS864US864&oq=writing+return+statements+in+javascript&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIICAEQABgWGB4yDQgCEAAYhgMYgAQYigUyDQgDEAAYhgMYgAQYigUyDQgEEAAYhgMYgAQYigUyDQgFEAAYhgMYgAQYigUyCggGEAAYgAQYogTSAQg3NTYwajBqN6gCALACAA&sourceid=chrome&ie=UTF-8 -->
## Sum of Positive

```js
function positiveSum(arr) {
  let sum= 0
  for (let i=0; i < arr.length; i++)
    if (arr[i] > 0){
      sum += arr[i]
    }
  }

positiveSum(arr)
```
<!-- Utlized Google to look up how to find the sum of an array to confirm that I should be using a "for" https://www.google.com/search?q=how+to+get+a+sum+of+an+array+in+javascript&sca_esv=d0c9352aa5174606&sca_upv=1&rlz=1C5CHFA_enUS864US864&sxsrf=ADLYWIJS3-Ea9fZidTT75DoO0j4wmPOisA%3A1726703185034&ei=UWbrZsbQAbbV5NoPicefqQs&ved=0ahUKEwiGvefP1s2IAxW2KlkFHYnjJ7UQ4dUDCA8&uact=5&oq=how+to+get+a+sum+of+an+array+in+javascript&gs_lp=Egxnd3Mtd2l6LXNlcnAiKmhvdyB0byBnZXQgYSBzdW0gb2YgYW4gYXJyYXkgaW4gamF2YXNjcmlwdDIGEAAYFhgeMgYQABgWGB4yBhAAGBYYHjIGEAAYFhgeMggQABiABBiiBEisQ1AAWOdBcAN4AZABAJgBoQGgAeIjqgEFMTguMje4AQPIAQD4AQGYAjCgAvgkwgIEECMYJ8ICChAjGIAEGCcYigXCAgoQABiABBhDGIoFwgILEAAYgAQYkQIYigXCAhEQLhiABBixAxjRAxiDARjHAcICDRAAGIAEGEMYyQMYigXCAgsQABiABBiSAxiKBcICBRAAGIAEwgIIEAAYgAQYsQPCAgsQLhiABBixAxiDAcICDhAAGIAEGLEDGIMBGIoFwgILEAAYgAQYsQMYgwHCAgcQABiABBgNwgIIEAAYFhgeGA_CAgsQABiABBiGAxiKBZgDAJIHBTIxLjI3oAfs1QI&sclient=gws-wiz-serp

Created code, which I couldn't get the output I wanted in VS Code, so I told ChatGPT what I wanted to do and asked it to check my code. It gave me some additions, which I utilized some of. I wasn't getting anything to pass on the Codewars Site. -->
## Function 2

```js
function square(num){
  console.log(num ** 2)
}

square(num)
```

## Sum Arrays

```js
function sum(arr){
  let sum= 0
  for (let i=0; i < arr.length; i++) 
  sum += arr[i]
}

sum(arr)
```

## Reversed Strings

```js
function reverseString(str){
  const splitString = str.split("")
  const reverseArray = splitString.reverse()
  const joinArray= reverseArray.join("")

return joinArray
}

reverseString(str)
```
<!-- Utilized a site to figure out how to reverse arrays, but was still not able to get it to yield a correct result on Codewars.
https://www.freecodecamp.org/news/how-to-reverse-a-string-in-javascript-in-3-different-ways-75e4763c68cb/ -->