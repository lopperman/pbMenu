# pbMenu
18-May-2025: Added 'Collapse()' and 'Expand()' actions, which enable vertically oriented pbMenu to collapse or expand from an external call.   External collapse and expand calls will work, even if pbMenu.EnableUserCollapse is set to false.  ('EnableUserCollapse' was previously called 'EnableCollapsedState'). 
18-May-2025: pbMenu.OnReset() is now called anytime the 'DefaultCollapsedstate' property changes, which forces menu collapsed state to match DefaultCollapsedState.
18-May-2025: Added 'IsBusyEnabled' property (Default=true).   When set to false, 'IsBusy' is completely ignored
18-May-2025: Additional refinement to pbMenu.Information()
18-May-2025: Added a 'QuickStart' guide 


