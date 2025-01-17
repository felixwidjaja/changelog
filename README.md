# Equinix Metal published images

Equinix Metal publishes images on the platform that have been built with the fleet's requirements in mind. These images are tested/validated against the fleet and are known to work with our metal. For most operating systems we publish fresh images on monthly basis, this guarantees a smooth user experience and reduces install times.

Images are kept as close to upstream releases as possible. It is not always possible (for a number of reasons) for us to publish a full changelog for every operating system which can be provisioned on our platform, but we strive to keep this changelog as comprehensive and up to date as possible.

# Changelog

The changelog aims to show what packages have changed since the last published image, what kernel and what deviations from upstream (if any) per new published image.

If there is any information that would be helpful but is missing from the changelog, [please raise an issue](https://github.com/equinixmetal-images/changelog/issues/new) and we will do our best to add it going forward.

# Equinix Metal Operating System Support Schedule

This is the list with latest details on the OSs Equinix Metal repackages and publishes for customers. Please, note that certain OSs, when they are approaching EOL (End Of Life) upstream, may not be supported in the newest hardware due to driver or other compatibility issues.

| OS                      | Version | Upstream EOL    | EM Estimated EOL |  Changelog                                                        | Notes                       |
| ---                     | ---     | ---             | ---              | ---                                                               | ---                         |
| AlmaLinux OS            | 8       | May, 2024       | Feb, 2024        | [x86_64](alma/x86_64/8.md) [arm64](alma/aarch64/8.md)             |                             |
| Alpine                  | 3       | Nov, 2023       | Aug, 2023        | [x86_64](alpine/x86_64/3.md) [arm64](alpine/aarch64/3.md)         |                             |
| CentOS                  | 7       | Jun, 2024       | Mar, 2021        | [x86_64](centos/x86_64/7.md)                                      |                             |
| CentOS                  | 8       | Dec, 2021       | Dec, 2021        | [x86_64](centos/x86_64/8.md)                                      |                             |
| Debian                  | 10      | Jun, 2024       | Mar, 2024        | [x86_64](debian/x86_64/10.md) [arm64](debian/aarch64/10.md)       |                             |
| Debian                  | 11      | Jun, 2026       | Mar, 2026        | [x86_64](debian/x86_64/11.md) [arm64](debian/aarch64/11.md)       |                             |
| Flatcar Linux           | stable  | Rolling release | N/A              | TBD                                                               | Coming soon                 |
| Nixos                   | 21.11   | Dec, 2021       | TBD              | TBD                                                               |                             |
| RedHat Enterprise Linux | 7       | N/A             | Aug, 2021        | [x86_64](rhel/x86_64/7.md)                                        |                             |
| RedHat Enterprise Linux | 8       | May, 2024       | N/A              | [x86_64](rhel/x86_64/8.md)                                        |                             |
| Rocky Linux             | 8       | May, 2024       | Feb, 2024        | [x86_64](rocky/x86_64/8.md) [arm64](rocky/aarch64/8.md)           |                             |
| Talos                   | 1.2.3   | Sep, 2026       | Sep, 2026        | [Changelog](talos/v1.md)                                          |                             |
| Ubuntu                  | 18.04   | Apr, 2028       | Jan, 2028        | [x86_64](ubuntu/x86_64/18_04.md) [arm64](ubuntu/aarch64/18_04.md) |                             |
| Ubuntu                  | 20.04   | Apr, 2030       | Jan, 2030        | [x86_64](ubuntu/x86_64/20_04.md) [arm64](ubuntu/aarch64/20_04.md) |                             |
| Ubuntu                  | 22.04   | Apr, 2032       | Jan, 2032        | [x86_64](ubuntu/x86_64/22_04.md) [arm64](ubuntu/aarch64/22_04.md) |                             |
| VMware ESXi             | 6.7     | Oct, 2022       | Aug, 2022        | N/A                                                               | Not available on latest HW. |
| VMware ESXi             | 7.0     | Apr, 2025       | Jan, 2025        | TBD                                                               |                             |
| VyOS                    | TBD     | ???             | ???              | TBD                                                               | Coming soon                 |
| Windows Server          | 2019    | Jan, 2024       | Sept, 2023       | [x86_64](windows/x86_64/2019.md)                                  |                             |
| Windows Server          | 2022    | Oct, 2026       |                  | [x86_64](windows/x86_64/2022.md)                                  |                             |

