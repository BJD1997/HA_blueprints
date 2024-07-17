# Aqara Smoke Detectors

[Aqara smoke detectors](https://www.aqara.com/en/product/smart-smoke-detector/) have the ability to alarm each other once one has detected fire.
Since this linkage as achieved through the aqara hub, Home Assistant now has to take care of that job.

- Created for zigbee2mqtt
- Linkage_alarm needs to be enabled/set to true for each device
- Needs each device (smoke detector) to be assigned to a room in order to be correctly notified which device was triggered in which room
- Select the smoke detectors you want to link
- Also mutes all the smoke detectors when one is muted.
- (Optional) Select actions to be executed when smoke is detected (i.e. turning on the lights) or the alarm muted.

---

This is a fork of [ciB](https://community.home-assistant.io/u/cib) [blueprint](https://community.home-assistant.io/t/aqara-smoke-detector-linkage-alarm-plus-optional-actions/750785) for the Aqara Smoke detectors.
Thanks for the work!
