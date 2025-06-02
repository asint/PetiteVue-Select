# PetiteVue-Select
A smaller 'nicer' &lt;select&gt; replacement

Many times have I seen huge overheads just to get a couple of "nicer" select components.
Petite-Vue is a great way to get started with just a little bit of Vue (just 6k), and it is
small enough to be used in a single page application without the overhead of a full
framework.

# Use
Just copy the snippet script into the base of your body and add the following html where you wish

```HTML
<div
  v-scope="Drop({ value: 'one', options: [{ value: 'one', label: 'One', icon: 'icon-One' }, { value: 'two', label: 'Two', icon: 'icon-One' }] })"
></div>
```
