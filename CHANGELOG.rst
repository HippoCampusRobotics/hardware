^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package hardware
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* moved to separate repo
* make startup sequence less epilepsy triggering
* speedup startup sequence
* fixed threading related typo in spotlight node
* added a bit of logging
* changed startup sequence service signature
* added startup sequence service to indicate boot process is done
* streamlined ov9281 launch
* launch file cleanup
* actually use the teensy config file
* migrated to microXRCEAgent
* ditched yapf
* added nsh_node to hippo launch setup
* added mavlink-routerd to hippo hardware setup
* fixed typo
* added reboot service name
* added reboot service for fcu
* added node as interface for the nuttx shell
* set sim time to false for hardware setup
* added hippo launch file
* updated mjpeg default settings for front camera
* added vertical camera launch file for buddy pi
* fixed wrong paranthesis
* mjpeg_cam update
* added missing paranthesis
* replaced math operations with bitshifts
* barometer now publishes also temperature
* fixed wrong decimal conversion
* fixed wrong exponential and adc addresses
* renamed PassLaunchArguments to something more descriptive
* added pre-commit hooks
* added licenses and applied formatting to all source files
* made header definition inline
  avoids potential problems with definition in header files.
* added license text
* initial version of barometer node
* use manually scoped non-scoped enum.
  no typecasts are required and still not polluting the namespace -> okay
  solution.
* moved model to class scope
* implemented oversampling as enum class
* changed return type to status
  Keep return types indicating execution status consistent.
* added second order temperature compensation
* initial ms5837 interface
* added tilt subscriber to camera_servo node
* added brightness subscriber to spotlight node
* substituted v4l2_camera with mjpeg_camera
* hardware launch file for bluerov added
* add spotlight node for bluerov + typo fixes to camera servo node
* log exception
* fixed pwm range
* fixed range list error
* added parameter range
* added camera servo node
* added gripper command handler
* added qos for subscription
* removed unused package install
* added newton gripper interface
* Contributors: Daniel Duecker, Thies Lennart Alff
