# zalando-womenplus-notes
## Notes for the course
### Week 3 Day 4
You can add null to an ArrayList in Java at any point, as long as the ArrayList's type allows for it. Here are some common scenarios where adding null to an ArrayList might be appropriate:

When the ArrayList Allows Nulls: By default, ArrayList in Java allows null values to be added. So, you can add null without any issues, like this:

```
ArrayList<String> list = new ArrayList<>();
list.add("Item 1");
list.add(null);
list.add("Item 3");
```
In this example, we've added a null value between two strings.

As a Placeholder: You can use null as a placeholder for elements that you intend to fill in later. For instance, if you're dynamically building a list and haven't determined the values yet, you can add null as a temporary placeholder:

```
ArrayList<Person> people = new ArrayList<>();
people.add(new Person("Alice"));
people.add(null); // Placeholder for a person to be added later
```

When You Need to Indicate Missing Data: If you have a collection of objects, and some elements don't have meaningful values or are missing, you can use null to represent that absence:

```
ArrayList<Integer> scores = new ArrayList<>();
scores.add(100);
scores.add(null); // No score assigned yet
scores.add(85);
```

However, you should always be cautious when using null values in collections because they can lead to NullPointerExceptions if not handled properly. Before accessing an element.

This line is a test commit. 
