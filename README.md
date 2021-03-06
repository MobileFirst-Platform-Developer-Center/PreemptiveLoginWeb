IBM MobileFirst Platform Foundation
===
## PreemptiveLoginWeb
A sample application demonstrating use preemptive login APIs.

### Tutorials
https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/authentication-and-security/user-authentication/

### Usage

1. Use either Maven, MobileFirst CLI or your IDE of choice to [build and deploy the available `ResourceAdapter` and `UserLogin` adapters](https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/adapters/creating-adapters/).

 The UserAuthentication Security Check adapter can be found in https://github.com/MobileFirst-Platform-Developer-Center/SecurityCheckAdapters/tree/release80.

2. From a command-line window, navigate to the project's root folder and run the command: `mfpdev app register web com.sample.preemptiveloginweb`.

3. You can either set-up a [Web development environment](https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/setting-up-your-development-environment/web-development-environment) that fits your needs, or use the provided Node.js-based reverse proxy.

#### WebSphere Liberty or Node.js
Follow the [Setting up the Web development environment](https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/setting-up-your-development-environment/web-development-environment) tutorial.

#### Using the provided Node.js-based reverse proxy
 - Make sure you have Node.js installed.
 - Navigate to the sample's root folder and run the command: `npm install` followed by: `npm start`.

3. In the MobileFirst Console → PreemptiveLoginWeb → Security, map the `accessRestricted` scope to the `UserLogin` security check.
4. In a browser, load the URL [http://localhost:9081/sampleapp](http://localhost:9081/sampleapp).

### Supported Levels
IBM MobileFirst Platform Foundation 8.0

### Third Party
This sample makes use of:

* Nodejs to load RequireJS
* RequireJS to load the MobileFirst SDK

### License
Copyright 2016 IBM Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
