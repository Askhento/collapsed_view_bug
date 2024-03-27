# collapsed-view-bug README

Showing collapsed view bug

### Steps to reproduce

0. run extension with F5
1. click on Zap icon with title "TEST_VIEW_CONTAINER"
2. It should contain 3 views with visibility : [visible, collapsed, hidden]
3. Change view location by dragging somewere and change collapsed state
4. From command palette run : "View: Reset View Locations"
5. Views will jump back but visibility option will not reset.
