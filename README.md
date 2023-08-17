# pcg_with_xorshift
32-bits pcg_with_xorshift random number generator
## simple random number generator,without std lib
### usage:
use pcg_with_xorshift::{PcgWithXorshift, RandomNumberGeneratorEngine};<br />
fn main() {<br />
    let mut pcg = PcgWithXorshift::new(None);<br />
    let number = pcg.get();<br />
}<br />

## reference:  
https://www.pcg-random.org/    
https://github.com/flo-at/rustsnake.git
