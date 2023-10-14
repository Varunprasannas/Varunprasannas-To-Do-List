import React from 'react';

const ToDoList = ({ toDoItems }) => {

    return (
        <ul>
            {toDoItems.map(({id, content, complete}) => (
                <Item id={id} content={content} complete={complete}/>
            ))}
        </ul>
    );
}

export default ToDoList;
