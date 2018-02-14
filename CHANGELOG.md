# Changelog

## [3.0.0] UNRELEASED
- `GetMyIP` now returns `net.IP` instead of `string`.
- `CalcHoneyScore` now accepts `net.IP` instead of `string`.
- `GetDNSResolve` now returns `map[string]*net.IP` instead of `map[string]string`.
- `GetDNSReverse` now accepts `[]net.IP` instead of `[]string`.

## [2.0.4] STABLE
- Dropped support for old golang versions (`1.1` - `1.5`).
- `GetHttpHeaders` is renamed to `GetHTTPHeaders`.
- Invalid url will now `panic`.
- Stream methods no longer return error.