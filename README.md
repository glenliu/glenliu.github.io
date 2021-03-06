# glenliu.github.io
initial page

|test table|col2|col3|
|----------|----|----|
|row1      |1.2|1.3|
|row2       |2.2|2.3|


|  Sequence   | Result                                                        |
|-------------|---------------------------------------------------------------|
| `a?c` <br>      | Matches `abc`, `axc`, and `aac`. Does not match `ac`, `abbc`,<br> | 
|             | or `a/c`.                                                     |
|-------------|---------------------------------------------------------------|
| `a*c`       | Matches "ac", "abc" and "azzzzzzzc". Does not match "a/c".    |
|-------------|---------------------------------------------------------------|
| `foo...bar` | Matches "foobar", "fooxbar", and "fooz/blaz/rebar". Does not <br> |
|    <br>         | match "fo/obar", "fobar" or "food/bark".                      |
|-------------|---------------------------------------------------------------|
| `....obj` <br>  | Matches all files anywhere in the current hierarchy that end  <br>|
|   <br>          | in ".obj". Note that the first three periods are interpreted  <br>|
|   <br>          | as "...", and the fourth one is interpreted as a literal "."  <br>|
|   <br>          | character.                                                    |
|-------------|---------------------------------------------------------------|

$$ x^2+y^2=r^2 $$

