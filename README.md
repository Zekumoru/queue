# Queue

A simple queue implementation in JavaScript.

## Documentation

### Constructor

```js
Queue()
```

Creates a queue.

### Members

#### size

Returns the size/length of the queue.

### Methods

#### enqueue

```js
enqueue(value)
```

Enqueues the given `value` to the queue. Returns `undefined`.

**Time complexity**: O(1)

**Space complexity**: O(1)

#### dequeue

```js
dequeue()
```

Returns the first enqueued value from the queue and removes it.

**Time complexity**: O(1)

**Space complexity**: O(1)

#### peek

```js
peek()
```

Returns the first enqueued value from the queue. It **does not** remove it from the queue.

**Time complexity**: O(1)

**Space complexity**: O(1)
