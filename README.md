Saixiii - https://saixiii.com

https://saixiii.com/line-robot-unofficial/
https://saixiii.com/chapter1-line-bot-python-api-official/
https://saixiii.com/chapter2-line-api-official/
https://saixiii.com/chapter3-line-api-reference/
https://saixiii.com/chapter4-line-api-webhook/
https://saixiii.com/chapter5-line-api-send-message/
https://saixiii.com/chapter6-line-python-sdk/

credit : carpedm20

LINE
----

[![Join the chat at https://gitter.im/carpedm20/LINE](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/carpedm20/LINE?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

- Documentation : [http://carpedm20.github.io/line/](http://carpedm20.github.io/line/)
- Developer Mailing List: [Google Group](https://groups.google.com/forum/#!forum/line-python-developer)

*May the LINE be with you...*


Update
------

**2015.05.28**

`sendImage` and `sendImageWithURL` is fixed.

To send an Image:

    >>> contact = client.contacts[0]
    >>> contact.sendImage('./image.jpg')

Or use:

    >>> contact = client.contacts[0]
    >>> contact.sendImageWithURL('https://avatars3.githubusercontent.com/u/3346407?v=3&s=460')


**2015.03.31**

authToken expiration [issue](https://github.com/carpedm20/LINE/issues/9) solved.

update authToken **automatically**:

    $ pip install line --upgrade

There is nothing to change in your original code.

update authToken **manually**:

    $ pip install line --upgrade
    $ python
    >>> from line import LineClient, LineGroup, LineContact
    >>> client = LineClient("ID", "PASSWORD")
    >>> client.updateAuthToken() # manual update
    True


**2014.08.08**

Some codes are removed because of the request of LINE corporation. You can use library only with `authToken` login.


Screenshot
----------

![alt_tag](http://3.bp.blogspot.com/-FX3ONLEKBBY/U9xJD8JkJbI/AAAAAAAAF2Q/1E7VXOkvYAI/s1600/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA+2014-08-02+%E1%84%8B%E1%85%A9%E1%84%8C%E1%85%A5%E1%86%AB+10.47.15.png)


Author
------

Taehoon Kim / [@carpedm20](http://carpedm20.github.io/about/)
