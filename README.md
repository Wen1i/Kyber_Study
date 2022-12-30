# CBD函数
![image](https://user-images.githubusercontent.com/104118101/210053629-d887738b-ca67-40d9-bd9e-6bb6230b77af.png)

```
static uint32_t load32_littleendian(const uint8_t x[4])
{
  uint32_t r;
  r  = (uint32_t)x[0];
  r |= (uint32_t)x[1] << 8;
  r |= (uint32_t)x[2] << 16;
  r |= (uint32_t)x[3] << 24;
  return r;
}
```
