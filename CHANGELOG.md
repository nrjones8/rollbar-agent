# Change Log

**0.3.11**
- Add option to delete files once they are fully processed. See [#22](https://github.com/rollbar/rollbar-agent/pull/22)

**0.3.10**
- Fix a bug where we weren't releasing the state file before recreating it. See [#17](https://github.com/rollbar/rollbar-agent/issues/17)

**0.3.9**
- Fall back to rollbar-agent's access token if a loaded item payload doesn't contain one

**0.3.8**
- Properly clean up state file when log files are deleted

**0.3.7**
- Fix issues when payloads contain unicode

**0.3.6**
- Output a helpful error message if the configuration file isn't found on load

**0.3.5**
- Allow configurable log levels to be defined

**0.3.4**
- Added 'warn' log level

**0.3.1**
- Added skip_to_end option. "Go through existing log files and save them in the state without processing them, so you do not process existing log info next run. Exits after processing once."
