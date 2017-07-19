# swupd Cookbook

This cookbook extends the `package` resource to work with clearlinux nodes.

# Requirements
## Platforms
ClearLinux

# Usage
This cookbook has no recipes.

# Resources
## package
Install bundles using `swupd` in ClearLinux nodes

```ruby
package 'ruby-basic' do
  action :install
end

package 'c-basic' do
  action :remove
end

package 'os-core' do
  action :upgrade
end
```

# License and Authors
Author:: Alberto Murillo (alberto.murillo.silva@intel.com)

Copyright 2017, Intel Corporation

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```