..
      Licensed under the Apache License, Version 2.0 (the "License"); you may
      not use this file except in compliance with the License. You may obtain
      a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
      WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
      License for the specific language governing permissions and limitations
      under the License.

Description
-----------
 This is a more complex example which shows:
    * ResourceGroup containing nested stacks
    * SoftwareConfig inside group-member nested stacks
    * SoftwareDeployments resource, in a nested template, configuring the whole cluster
    * Using the environment to map nested templates via type aliases
    * Parameter defaults specified in the environment

Run the example like this:

    * heat stack-create rg123 -f resource_group.yaml -e environment.yaml

You may need to adjust the parameter_defaults in environment.yaml to suit your environment.
