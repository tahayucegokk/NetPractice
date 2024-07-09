# Level 1

| Subnet |         IP          |
|--------|---------------------|
| A1     |   104.94.23.11      |
| B1     |                     |
| C1     |                     |
| D1     |   211.191.191.74    |

# Level 2

| Subnet |         IP          |       Mask        |
|--------|---------------------|-------------------|
| A1     |   192.168.36.221    |                   |
| B1     |                     |  255.255.255.224  |
| C1     |   192.168.1.2       |                   |
| D1     |   192.168.1.1       |                   |

# Level 3

| Subnet |         IP          |       Mask        |
|--------|---------------------|-------------------|
| A1     |                     |  255.255.255.128  |
| B1     |   104.198.243.124   |  255.255.255.128  |
| C1     |   104.198.243.123   |                   |
| S1     |                     |                   |

# Level 4

| Subnet |         IP          |       Mask        |
|--------|---------------------|-------------------|
| A1     |                     |  255.255.0.0      |
| B1     |   119.105.121.193   |  255.255.0.0      |
| R1     |   119.105.116.91    |  255.255.0.0      |
| R2     |                     |                   |
| R3     |                     |                   |
| S1     |                     |                   |

# Level 5

| Subnet |         IP          |        Mask        |
|--------|---------------------|--------------------|
| A1     |    31.107.129.125   |    255.255.255.128 |
| B1     |    167.119.116.253  |    255.255.192.0   |
| R1     |                     |                    |
| R2     |                     |                    |


| Route |   Gateway   |
|-------|-------------|
|  Ar1  | 31.107.129.126 (default) |
|  Br1  | 167.119.116.254 |

# Level 6

| Subnet                  |         IP          |        Mask        |
|-------------------------|---------------------|--------------------|
| A1                      |                     |   255.255.255.128  |
| R1                      |    67.150.218.226   |                    |
| R2                      |                     |                    |
| S1                      |                     |                    |
| I1                      |                     |                    |

| Route |   Gateway     |
|-------|---------------|
|  Ar1  | 67.150.218.226 (default) |
|  Rr1  | default       |
|  Ir1  | 67.150.218.0/0 |

