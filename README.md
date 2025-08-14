# Lightweight-Cryptographic-Protocols-for-Low-Power-IoT-Devices-ML-
This project examines lightweight and ultra-lightweight cryptographic algorithms for constrained devices like IoT, RFID, and embedded systems, offering implementations, performance evaluations, and comparisons to guide efficient encryption choices for low-power, resource-limited environments without sacrificing security.


# Lightweight and Ultra-lightweight Cryptographic Algorithms

## Overview
This repository presents implementations and performance analysis of lightweight and ultra-lightweight cryptographic algorithms designed for constrained environments like IoT devices, RFID systems, and embedded platforms. The aim is to provide secure encryption solutions that consume minimal resources while maintaining strong data protection.

## Features
- Implementations of multiple lightweight and ultra-lightweight encryption algorithms
- Performance benchmarking on speed, memory usage, and power efficiency
- Comparative analysis with conventional cryptographic methods
- Documentation for easy understanding and usage
- Code examples for integration in resource-limited systems

## Applications
- Internet of Things (IoT) security
- RFID authentication
- Embedded system data protection
- Wireless sensor networks
- Low-power secure communications

## Getting Started
```bash
# Clone this repository
git clone https://github.com/yourusername/lightweight-crypto.git

# Install required dependencies
pip install -r requirements.txt

# Run example scripts
python examples/algorithm_test.py
```

## Contributing -

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.

## License -

This project is licensed under the MIT License.

----Comparison Table---

```bash
| Algorithm      | Speed (Encryption) | Memory Usage | Security Level |
| -------------- | ------------------ | ------------ | -------------- |
| PRESENT        | High               | Very Low     | Medium         |
| SPECK          | Very High          | Low          | Medium         |
| SIMON          | Very High          | Low          | Medium         |
| CLEFIA         | Medium             | Medium       | High           |
| AES-128 (Lite) | Low                | High         | High           |
| KATAN          | Medium             | Very Low     | Low            |

```

**Insights**

* SPECK and SIMON offer excellent speed and low memory usage, making them ideal for ultra-constrained devices.

* CLEFIA balances moderate speed with high security, suitable for mid-range IoT devices.

* PRESENT is optimized for very low memory but offers only medium security.

* AES-128 (Lite) provides high security but is less suitable for low-power devices due to higher memory and computational requirements.

* KATAN is memory-efficient but offers lower security, so it’s better for short-term or low-sensitivity data.

**Use-Case Examples**

 * PRESENT → RFID authentication systems where memory is extremely limited.

 * SPECK / SIMON → Sensor nodes in wireless sensor networks requiring fast data encryption with minimal resources.

  * CLEFIA → Smart home devices that need a balance between security and efficiency.

  * AES-128 (Lite) → Medical IoT devices transmitting highly sensitive data.

  * KATAN → Temporary secure data transmission in low-security applications like simple asset trackers.

**Conclusion**

* Lightweight and ultra-lightweight cryptographic algorithms enable secure communication in resource-constrained environments.

* The choice of algorithm depends on the device’s hardware limitations, required security level, and application domain.

* For most ultra-low-power IoT applications, SPECK and SIMON provide the best trade-off, while CLEFIA and AES-128 (Lite) serve higher-security needs where resources allow.

