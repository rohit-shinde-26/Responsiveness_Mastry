# Responsiveness_Mastry
Responsiveness Mastry with RedNos (Using Pure Vanilla CSS)


## 1. Understanding Units
### 1. Px
It has fixed size, it cant changes 

### 2. %
It gives size upon parents size <br/>
Ex : Children gives 20% size of its parent

### 3. Vw => ViewPort Width
It changes width according to its screen size

### 4. Vh => ViewPort height
It changes height according to screen

### 5. Vmax => ViewPort Maximum
It works like Vw but when width is minimun than height it works like Vh.

### 6. Vmin => ViewPort Minimum
It works like Vh but when height is minimum then width it works like Vw.

### 7. em
It takes same size of its parent <br/>
Ex : Font-size : 2em; // It takes 2x size of its parent

### 8. rem 
Takes size as screen size <br/>
1rem = 16px;



## Absolute vs Flexbox
### Why not maximum use absolute ?
Because it mostly thrown an error while time of responsive


### Why use flexbox ?
It is easier simple tool for making responsiveness

### Some flexbox ex
```ruby
display: flex; 
```
     makes child is in row form  <br/>

```ruby
flex-direction: column; 
```
     makes child is in column form  <br/>

```ruby
align-items: center;  
```
     centered element on Y axis  <br/>

```ruby
justify-content: center; 
```
     centered elements on x axis <br/>

```ruby
justify-content: space-evenly;
```
     same space on child  <br/>

```ruby
flex-wrap: wrap;
```
     when childs are very close then it was send to down  <br/>