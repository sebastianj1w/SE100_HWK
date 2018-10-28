<div  align="center">
<img src="/logo.png" width="200" height="200" />
</div>

# Vue

## What is Vue

> Vue.js is a progressive framework for building user interfaces. Unlike other heavyweight frameworks, Vue uses ***bottom-up incremental design***. Vue's core libraries ***focus only on the view layer and are very easy to learn and integrate with other libraries or existing projects.*** On the other hand, Vue is fully capable of driving complex single-page applications using single-file components and libraries supported by the Vue ecosystem.
> The goal of Vue.js is to implement the response data binding and composite view components through the simplest API.

## Pros & Cons

What I've written above comes from the internet, it looks like a bit of a sham, and then it's my real feeling in learning.

### Pros

During a few days' learning, I got some advantages of Vue.

#### 1. Easy to learn

People who only know some knowledge of HTML, JavaScript and CSS can get to Vue quickly. As for me, I got confused when I try to use other frameworks of front-end development, but I felt comfort to learn Vue. I think the reason of this feeling is that ***Vue is lightweight and concise compared to others***.

#### 2. Easy to use

Using Vue, it is easy to creat complex applications though I'm new to front-end development.

For example, I want to write a simple  page which has a input box and a line of words, I want the words change when value of input box changes. It can be done with the feature of ***responsive data binding*** in a very easy and clear way.

```html
<div id="app">
    <input type="text" v-model="message">
    <hr>
    <p>{{ message }}</p>
</div>
<script type="text/javascript">
    var app = new Vue({
      el: '#app',
      data: {
        message: 'Hello Vue!'
      }
    })
</script>
```

Besides, by using `v-model` the binding is ***Bi-directional***. That is, the change of any of the two will change the other.

#### 3. Component-based development

I have developed the "WordLadder" project, I have a hard time dealing with many `<div>` labels and functions.

Vue.js splits a single page application into a single component through components. ***Just like in OOP***, this helps to aggregate and decouple.

Though I have not using Vue to develop a big porject but this obviously can be an advantage.

## 

### Cons

Because I use raw HTML + JS to write pages, and I just begin to learn Vue, I haven't found real disadvantage using it by myself. But *according to internet informations*, here are two main shortage of Vue.

#### 1. Community

There are many get-to-start tutorials, but high-end documents are rare. You may find it difficult to find a library that fits your requirement. On the contrast, React has many useful libraries. This may make Vue hard to use when developing really big projects. Besides, Vue lacks the support of IDEs.

#### 2. Support of big companies

With **Facebook's promotion**, learning React can bring more dividends in technology and resources than Vue.

___

## Ending

I didn't have enough time to fully learn Vue, and because I have no experience with other frameworks, Vue seemed almost entirely superior to bare JS, which led to the fact that the feeling was very personal. I would like to learn Vue and React more in next days and try to improve this file if I had time.
