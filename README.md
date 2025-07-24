# Geely Auto E245 - Flyme Auto Release Registry

This registry applies to the [Flyme Auto](https://www.flymeauto.com/) system developed by Meizu and deployed in the cars marketed as:

- Geely EX5
- Proton eMas 7
- Geely Galaxy E5

The brands and models above refer to the same car with code [E245](https://en.wikipedia.org/wiki/Geely_Galaxy_E5) manufactured by Geely Auto.

## Purpose

The purpose of this register is to serve as a centralized repository for understanding the evolution of the DHU and Flyme Auto software, as well as to keep track of release notes if they are made public.

## Limitations

- This registry is built based on user reports since Geely doesn't provide direct guidance or information about their releases and roadmap.
- Vehicle applications (such as Spotify, Energy, Phone, etc.) have their own versions. Based on user experience, it is possible for two cars to have the same Flyme Auto version installed but different versions of car applications. Tracking such variants of software bundles is more complex and is not included in this documentation repository.
- The car has different upgradable modules, including the underlying Android Automotive OS, this registry focuses on Flyme Auto (Flyme OS), which is the one users interact with.
- Dealerships in certain countries have visibility over upcoming features. Others are operating with little to no information al all.
- It has been reported that Geely releases frequent builds, however, Over-the-Air (OTA) updates are controlled by the dealerships on each country and not pushed to cars frequently. This should simplify the version landscape deployed across the fleet in the future, but for now any data available will be captured even if it is partial.

## Release Registry

The features or options tracked below are those of interest to most users:


| Version | Build    | Country    | Release Notes                                     | Apple CarPlay | Android Auto | adb Access | CarbitLink while Driving | AVAS Sound Options |
| --------- | ---------- | ------------ | --------------------------------------------------- | --------------- | -------------- | ------------ | -------------------------- | -------------------- |
| 1.1.0   | -        | Australia  | Unknown                                           | N¹           | N³          | Y          | Y                        | N                  |
|         | -        | Malaysia   | Unknown                                           | N¹           | N³          | Y          | Y                        | N                  |
|         | -        | Costa Rica | Unknown                                           | N¹           | N³          | Y          | Y                        | N                  |
| 1.1.2   | D513BF5F | Australia  | Unknown                                           | N¹           | N³          |            |                          |                    |
| 1.1.3   | 60F75E77 | Costa Rica | Unknown                                           | N¹           | N³          | N          | N⁶                      | N                  |
| 1.1.4   | 3B7B61D8 | Malaysia   | [Available](/Release-Notes/1.1.4_3B7B61D8_MYS.md) |               | N³          |            | Y                        | N                  |
| 1.1.5   |          | Australia  | [Available](/Release-Notes/1.1.5_AUS.md)          |               | N³          |            |                          | N⁵                |
|         | 9AFB221B | Malaysia   | Unknown                                           |               | N³          |            |                          | N                  |
|         | 24F4D77A | Costa Rica | Unknown                                           | N⁴           | N³          | N          | N                        | N                  |
| 1.1.6   |          | Australia  | Unknown                                           |               | N³          |            |                          |                    |
|         | C0CC88A1 | Malaysia   | [Available](/Release-Notes/1.1.6_C0CC88A1_MYS.md) | Y             | N³          | N          | N                        | Y                  |
|         | 5F811B06 | Costa Rica | Unknown                                           | Y             | N³          | N          | N                        | Y                  |
| 1.8.0.3 | FFF6979D | China      | Unknown                                           |               |              |            |                          |                    |

If cells in columns 2 to 9 are empty, it means the data is missing. If you have details to add, feel free to modify and create a Pull request.

## Notes

¹ Not officially available but can be enabled through the engineering menu (aka secret menu) using the car's phone application.<br>
² Not officially available but can be enabled through the engineering menu (aka secret menu) using the car's phone application. However, once enabled, the setting will not persist after a system shutdown or reset.<br>
³ Not officially available yet, but can be enabled through adb and Headunit Reloaded.<br>
⁴ Some users got a build installed by the dealership with Apple CarPlay enabled by default.<br>
⁵ AVAS sound cannot be customized but it has a new tone, different from the typical "ice cream truck".<br>
⁶ Version shipped from factory allows it, version installed by the dealership doesn't.
<br>

:warning: If you have [adb](https://developer.android.com/tools/adb) access and don't want to lose it, it is highly recommended to install [Geely EX5 Helper](https://eucalyptus-software-geely-ex5-mods.pages.dev/app-library?fbclid=IwY2xjawLt4rdleHRuA2FlbQIxMABicmlkETF5Zk9VaUhaMWljZ0wyTTI4AR4lZdZsNj7IQlUqDdamVBG2P3U6WChVTcrqTEsuYVpcr3UY5KDUiwF8V3x00g_aem_Ur9yQGfYOTxURHPlcOCHzg) before upgrading your car's software.
