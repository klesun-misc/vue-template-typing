# vue-template-typing
Just an idea for now - to make a webstorm extenstion that would show static typing errors in vue templates

Possibly could just use: https://github.com/Yuyz0112/vue-type-check (did not manage to get it working so far, it does not seem to work on windows ;c). Upd.: it seems to be just a wrapper for https://www.npmjs.com/package/vue-language-server

Supposedly will achieve this:
https://github.com/vuejs/vue-loader/issues/1561

And this:
https://github.com/vuejs/vetur/issues/209

Since issues were stale for 3 years now, I guess there is no point in waiting.

This is how coding vue templates in a typescript project works now:

![image](https://user-images.githubusercontent.com/30558426/81400361-8b9f7980-9135-11ea-9f22-d85c1465392a.png)

And this is what I'd like to achieve:

![image](https://user-images.githubusercontent.com/30558426/81400508-f355c480-9135-11ea-9a25-3b24d09fa0d6.png)


Would be also cool to add some annotation for mandatory parameters in a component...



Upd.: will probably make it a part of [deep-js-completion](https://github.com/klesun/deep-js-completion)


____________________

Another, completely unrelated idea: a game based on triangular tiles. There are orthogonal ones, hexagonal ones, isometric ones, but I never saw a trigonal grid game. May think of some unique game mechanics where you can choose one of three directions per turn...

![image](https://user-images.githubusercontent.com/5202330/84546274-ae5f1800-ad09-11ea-8946-5a6b05c382e3.png)
