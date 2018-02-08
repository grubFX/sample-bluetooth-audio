# Android Things Bluetooth Audio sample with FireBase connection

This sample demonstrates the use of Android Bluetooth APIs for audio from an Android Things app. It shows how to enable an A2DP sink on your Android Things device and control lifecycle events, such as pairing, connection and playback so that other devices, like a phone, can connect and play audio on your Android Things device. Further the capabilities of the [sample-button example](https://github.com/androidthings/sample-button) were implemented in order to use the button as a way to put the device into pairing mode and the LED to provide visual feedback on the actual state, the device is currently in. Further, a connection to a FireBase backend is used to store timestamps when devices last dis-/connected or the pairing button was pressed, along with the Bluetooth names of involved devices.

## License

Copyright 2017 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
