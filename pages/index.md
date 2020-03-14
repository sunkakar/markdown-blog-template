# Family and Friends 
##### A Data Science Blog by Sundeep Kakar


### Introduction 

[![Image from Gyazo](https://i.gyazo.com/35076e41e6eaa667988337697960226d.jpg)](https://gyazo.com/35076e41e6eaa667988337697960226d)

As an International student, my primary form of communication with family and friends is through WhatsApp. During the last 4 years at IUPUI, I travelled back to New Delhi, India, every year during **Summer Break** and **Winter Break**. I chose to take this opportunity to learn more about my communication skills. By examining the Chat Data with my mom, I wanted to answer the following questions:
* Am I a good communicator?
* How much am I contributing to the conversations?
* Are there any patterns that exist in our chat conversations?
  * Are there inconsistencies based upon my location (US or India) ?

### Beginning 

I collected the data by exporting my chat history from WhatsApp. According to [Express](https://www.express.co.uk/life-style/science-technology/1140438/whatsapp-export-chat-meaning-how-to-export-whatsapp-conversations-iphone-android), a maximum of 40,000 messages can be exported from a chat when choosing to export without media. Media accounts for larger chunks of the data and therefore doesn't allow enough space to go beyond about 10,000 messages in chat history. Using RegEx, the text was extracted and a functional dataset was built. This allowed for 

### Subject No. 1: My Mom

I chose to start with my mom. Talking to her is frequent over the phone/chat when I'm not in the states. The data exported for the chat spanned from August 2017 to February 2020. This allowed for a uniform dataset which can be compared for patterns every year given that I travel back during summer and winter break. I felt I didn't use chat communication with her when I was home in India but I didn't know if that was true. 

[![Image from Gyazo](https://i.gyazo.com/dc214053e903eff45b08993aea536626.png)](https://gyazo.com/dc214053e903eff45b08993aea536626)



[![Image from Gyazo](https://i.gyazo.com/e9fba84624f491e10ad8fb623d256413.png)](https://gyazo.com/e9fba84624f491e10ad8fb623d256413)



Clearly it can be observed that during break time I texted her the least. 
Next, let's look at the trends of how often I text her. 



Result:

*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

_You **can** combine them_

### Lists

**Inordered:**

    * Milk
    * Bread
        * Wholegrain
    * Butter

Result:

* Milk
* Bread
    * Wholegrain
* Butter

**Ordered:**

    1. Tidy the kitchen  
    2. Prepare ingredients  
    3. Cook delicious things

Result:

1. Tidy the kitchen  
2. Prepare ingredients  
3. Cook delicious things

### Images

    ![Alt Text](url)

Result:

![m'lady](http://i.imgur.com/v8IVDka.jpg)

### Links

    [link](http://example.com)
    
Result:

[link](http://example.com)

### Blockquotes

    As Kanye West said:

    > We're living the future so
    > the present is our past.

Result:

As Kanye West said:
> We're living the future so
> the present is our past.

### Horizontal Rules

    ---

Result:

---

### Code Snippets

    Indenting by 4 spaces will turn an entire paragraph into a code-block.

Result:

    .my-link {
        text-decoration: underline;
    }

### Reference Lists & Titles

    **The quick brown [fox][1], jumped over the lazy [dog][2].**

    [1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
    [2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

Result:

**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"


### Syntax Highlighting

    ```javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    ```

Result:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## References

* http://blog.ghost.org/markdown/
* https://guides.github.com/features/mastering-markdown/
