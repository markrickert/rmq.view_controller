rmq-tabbar-problem
===================

Steps to reproduce crash when getting `rmq.view_controller`:

1. `bundle`
2. `rake`
3. Type into the REPL: `rmq.view_controller`.
4. Switch to a new tab and try again.
5. Switch to the "more" tab and try again. Notice it returns a `UIMoreListController`.
6. Tap into a view controller in the more tab and try again.
7. Crash.
