
```<?php
$harder = true;
$discipline = true;
$try_to_execute = true
$hobbies = ["coding", "hiking", "archery", "jogging", "swimming"]
do {
  if($harder && $discipline && $try_to_execute) {
    echo "I can do it and make it better \n";
  }
  echo "His hobbies are ".implode(", ", $hobbies);
} while (true);
?>
```
