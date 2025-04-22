# Day-of-Dragons-Signatures

### 2025/3/13

目前所有特征码均能扫描成功。

### *float* fps_max
`?? ?? ?? ?? 00 00 70 42 98 8A B3 D4 F6 7F 00 00 80`

### entitylist

```
for (int i = 0; i < Entity::GetAll(); i++) {
    auto player = Util::PS("Dragons-Win64-Shipping.exe", 0x085CA2B0, 0x8, 0x8, 0x350 + i*0x10, 0x60, 0x0);
}
```
