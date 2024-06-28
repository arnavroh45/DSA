## Important Notes

### Middle Node and Loop Detection
- **Technique**: Hare and Tortoise approach
- **Usage**: Whenever asked to find the middle node or detect a loop in a linked list, use this approach.

### Maximum Sum of Subarray
- **Technique**: Reset on Negative Sum
- **Usage**: When finding the maximum sum of a subarray, if the current sum becomes negative, reset the sum to 0.

### Tree Structure and Indexing
- **Left Child Index**: `2i + 1`
- **Right Child Index**: `2i + 2`

### Tree Traversal Orders
- **Inorder Traversal**: `Left -> Root -> Right`
- **Preorder Traversal**: `Root -> Left -> Right`
- **Postorder Traversal**: `Left -> Right -> Root`

---

### Additional Information

#### Hare and Tortoise Approach
This technique involves using two pointers, one moving twice as fast as the other. It is particularly useful for:
- Finding the middle element of a linked list
- Detecting cycles in a linked list

#### Maximum Subarray Sum Algorithm
When calculating the maximum subarray sum (e.g., using Kadane's Algorithm):
- If the current sum becomes negative, reset the sum to 0.
