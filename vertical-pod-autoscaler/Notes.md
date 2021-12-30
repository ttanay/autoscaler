# Notes
The `TargetRef` for a VPA is an `autoscaling.CrossVersionObjectReference`.
Q: How is the validation done? How does it stop me from creating one for a Pod obj?
In fetcher.go