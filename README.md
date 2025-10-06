#HashMap - Vanier Programming 01
---

Q24: A HashMap is a class in java that can be use to create an object that can store data as values and pair them with a key. This key can be used to reference the data.
You use the HashMap by creating a HashMap object and using the put() method to put values that you associate with key into "buckets". You can then use the get() method to retrieve the value that is associated with the specified key.

Q25:get() and set(). Yes, I think the same datatype can be used.

Q26: Use the size() method.

Q28: It replaces the value with the new one.

Q29: You cannot give an entry two keys. If you make 2 entries with the same value but different keys, you will have made 2 entries.

Q30:
``` java
phoneBook.containsKey(name);
```

Q31: It returns *null*

Q32: A for-loop can be used:
``` java
for (String key : phoneBook.keySet(){
    System.out.printf(key);
}
```