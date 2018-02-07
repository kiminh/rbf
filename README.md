# RBF
Redis Bloom Filter

# Advantage

1. Scalable
2. Counting
3. CPU Cache Optimization

# Commands

### BFADD key member [member ...]

Add the specified members to the bloom filter stored at key.

Time complexity: O(1)

### BFEXISTS key member [member ...]

Returns if member exists.

 * 1 if the member exists
 * 0 if the member does not exist.

Time complexity: O(1)

### BFLEN key

Returns the number of members contained in the bloom filter stored at key.

Time complexity: O(1)

### BFDEL key [key ...]

Removes the specified keys. A key is ignored if it does not exist.

Time complexity: O(1)
