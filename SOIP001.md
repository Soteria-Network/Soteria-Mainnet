
✅ Recommendation for next release

    EWMA smoothing: Move from 1/3 → 1/2. This will make difficulty react faster without going unstable.

    Clamp bounds: Widen from −25%/+30% → −30%/+35%. This gives more responsiveness per block.

    minTarget Normal: Move from >>3 → >>4. This loosens the floor, allowing difficulty to rise higher if hashrate surges x16 instead of x8 the current value.

    dtUpper: Raise from 3*T → 4T*. This gives more tolerance for slow blocks, reducing artificial compression of long intervals.
