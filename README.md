# Zort

a lot of sorting algorithms in zig

| Algorithm | Implemented | ASC | DESC | No Allocation |
| ------------ | ------------- | ------------- | ------------- | ------------- |
| Quick | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Insertion | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Selection | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Bubble | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Shell | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Comb | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Heap | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Merge | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x: |
| Radix | :heavy_check_mark: | :heavy_check_mark: | :white_check_mark: (using mem.reverse) | :x: |
| Tim | :x: | :x: | :x: | :x: |
| Block | :x: | :x: | :x: | :x: |
| Cube | :x: | :x: | :x: | :x: |
| Tree | :x: | :x: | :x: | :x: |
| Patience | :x: | :x: | :x: | :x: |
| Smoothsort | :x: | :x: | :x: | :x: |
| Tournament | :x: | :x: | :x: | :x: |
| Stalin | :x: | :x: | :x: | :x: |
| Thanos | :x: | :x: | :x: | :x: |

## Usage:
```zig
const zort = @import("zort");

pub fn main() void {
    var arr = [_]u8{ 9, 1, 4, 12, 3, 4 };
    sort(u8, arr, false, .Quick, null);
}
```