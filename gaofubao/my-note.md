
go build
- -gccgoflags "-N -l" 关闭内联优化
- -ldflags "-s -w" 关闭调试信息