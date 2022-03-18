https://www.w3schools.com/jsref/dom_obj_event.asp
Viết thẳng vào thẻ

Assign event using the element node:
element.eventName = () =>{

}

1. Query cái thẻ cần gán event
2. gắn vào thẻ bằng element

preventDefault() :
ngăn chặn hành vi default của tag
ví dụ <a href=""> thì href sẽ ko diễn ra

StopPropagation():

 ví dụ: onclick bên trong có thể bị gọi bởi onclick bên ngoài