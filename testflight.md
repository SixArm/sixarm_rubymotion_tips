
# TestFlight

To log with TestFlight vs. stdout:

```
def log(msg)
  if Object.const_defined?('TestFlight')
     TFLog(msg)
  else
    if DEBUG
      p "#{Time.stamp} log: #{msg}"
      $stdout.flush
    end
  end
end
```
