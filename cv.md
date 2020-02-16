# CV #
# Olga Turko #
## Front-end developer ##

+375292789301
olchiktur@yandex.ru

## 1. My goal ##
Aways learning new things from everywhere

## 2. Skills ##
HTML, CSS, JavaScript, CitHub, VSCode

## 3. Code example ##
```function getCounter(v) {
  var A = {};
  A.value = (v || 0);
  
  A.log  = function () {
		  console.log(A.value);
	  return this; 
  };
  
  A.count = function (val) {
		 A.value += val;
	    return this; 
  };
  
  A.reset = function() {
		  A.value = 0;
	  	return this; 
  };
  
  return A;
}

var counter = getCounter(5);

counter.log().count(4)
  .log() // 9
  .count(3)
  .log() // 12
  .reset()
  .log() // 0
  .count(8)
  .log(); // 8
```
## 4. English ##
Pre-intermediate(A2)
