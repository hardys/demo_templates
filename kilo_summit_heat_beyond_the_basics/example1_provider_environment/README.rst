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
 This is example demonstrates how to use environments:
    * Defining parameters via the environment
    * How to define a provider resource nested stack via the environment

You can launch the stack using the python-heatclient CLI:
    * heat stack-create example1 -f stack.yaml -e environment.yaml
