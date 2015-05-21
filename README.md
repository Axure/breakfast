# Breakfast / 约早饭

## Tech Stack

We use **Ruby on Rails** for the backend and **React** for the view.

## RESTful API

> 
> 

Address           | Use
----------------- | -------------
/user/:id/follow  | Content Cell
/user/:id/        | Content Cell

External requests are limited.

## Application Structure

```flow
st=>start: Start:>https://www.zybuluo.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```