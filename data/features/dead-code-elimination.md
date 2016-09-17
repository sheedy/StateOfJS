While code splitting lets you split up your file and only send out the parts that are needed, **dead code elimination** goes one step further and digs into your codebase to remove unneeded code altogether. 

Now, instead of importing the entire [Underscore](http://underscorejs.org/) library, you can have a tool like [Rollup](https://github.com/rollup/rollup) go through the Underscore code and get rid of any function you're not actually using before bundling the whole thing up. 