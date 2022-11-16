<script>
    // @ts-nocheck
    import TodoItem from "$lib/todo-item.svelte";
    
    const title = 'ToDos'
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>

<form action="" method="">
    <input type="text" name="text" aria-label="Add a ToDo" placeholder="+ Tap to add a ToDd">
</form>

<TodoItem />
<TodoItem />
<TodoItem />