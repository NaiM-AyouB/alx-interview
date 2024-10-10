# Can Unlock All

This project contains a function that checks if all boxes in a series can be unlocked. Each box may contain keys to other boxes.

## Files

- `can_unlock_all.py`: Contains the function `canUnlockAll(boxes)`.

## Usage

The function takes a list of lists as input, where each sub-list contains keys for other boxes. The function returns `True` if all boxes can be unlocked, and `False` otherwise.

### Example

```python
boxes = [[1], [2], [3], []]
print(canUnlockAll(boxes))  # True
