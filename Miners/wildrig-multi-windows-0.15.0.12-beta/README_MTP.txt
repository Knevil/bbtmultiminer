[ ENGLISH ]

SOFTWARE PROVIDED AS IS WITH NO WARRANTIES OR ANY RESPONSIBILITY

Lines above for MTP algo for ZCoin

8GB of RAM is MUST HAVE. Same for GPU, 8Gb only cards. 4Gb will be too slow.

Current implementation generate MerkleTree on CPU, that's why good to get fast CPU and put GPU's into x16 PCI-E. Otherwise big rigs(6+ GPU's) will spend lot of time for generating MerkleTree and transferring data into GPU, because pools send lot of new jobs sometimes.

Because of this powerdraw is unstable, while data is transferring to GPU, GPU's running at low powerdraw. If you think this is bad for your hardware - don't use the miner. But there us parameter --mtp-stable-power, which will make miner hash all the time to avoid those jumps, so it can help.



[ RUSSIAN ]

���� ��������������� ��� ���� ��� �����-���� �������� � ���������������

����� ���� ��� ��������� MTP ������ ZCoin

8�� ����������� ������ �����������. ���� �������� � ���������, ������ 8�� ����� ����� �������� ������. 4�� � ��� ������ ���������.

������� ���������� ���������� MerkleTree �� ����������, ������� ��� ��������� ����������� ����� ������� ��������� � ���������� ����������� � x16 PCI-E. ����� ������� ����� �� ������� �����(�� 6 ����) ������� ����� ������� �� ��������� MerkleTree � ���������� ������, �.�. ���� ����� ����� �������� ����� ������.

��-�� ����� ����������� ������� �����������, ���� ������ ������������ �� ����������, ���� ����� �������� � ������ ����������������, ��� �������� �� ����� ������ ��� ���������. ����������� ������ �� ���� ����� � ����. ��� �� ���� �������� --mtp-stable-power, �� �������� ������ ��������� ����������, ��� ����� ��� ������ � ��������� �������.