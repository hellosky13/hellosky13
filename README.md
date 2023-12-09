Writing Queue and Priority Queue


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~




import queue



# Step 1: Create a Queue

my_queue = queue.Queue()


# Step 2: Create an object for that queue (Already done in Step 1)


# Step 3: Add an element to the queue

element_to_add = "Hello, World!"

my_queue.put(element_to_add)

# Step 4: Pop an element from the queue

popped_element = my_queue.get()



# Step 5: Show the output

print("Element added to the queue:", element_to_add)

print("Element popped from the queue:", popped_element)



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~






import queue

# Create a Priority Queue
priority_queue = queue.PriorityQueue()

# Create an object for the Priority Queue (Already done in create a Priority Queue)

# Add an element to the Priority Queue
priority_queue.put((3, "Apple"))
priority_queue.put((1, "Samsung"))
priority_queue.put((2, "Nokia"))

# Pop an element from the Priority Queue
popped_element = priority_queue.get()


print("Added elements to the Priority Queue:")
print("(3, 'Apple'), (1, 'Nokia'), (1, 'Samsung')")

print("Popped element from the Priority Queue:", popped_element)



