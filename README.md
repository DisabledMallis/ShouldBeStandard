# ShouldBeStandard
A C++ library implementing standard proposals that I like

## sbs::breakpoint
Inspired by the [std::breakpoint proposal](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2022/p2514r0.html) by René Ferdinand Rivera Morell and Isabella Muerte

### Example
```
#include <debugging>

int main()
{
  sbs::breakpoint();
}
```
