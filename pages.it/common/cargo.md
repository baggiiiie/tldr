# cargo

> Gestore di pacchetti di Rust.
> Gestisce progetti Rust ed i moduli dai quali sono dipendenti (detti crate).
> Alcuni comandi aggiuntivi, come `build`, hanno la propria documentazione.
> Maggiori informazioni: <https://doc.rust-lang.org/cargo>.

- Cerca una crate:

`cargo search {{termine_di_ricerca}}`

- Installa una crate:

`cargo install {{nome_crate}}`

- Elenca crate installate:

`cargo install --list`

- Crea un nuovo progetto Rust binario o di libreria nella directory corrente:

`cargo init --{{bin|lib}}`

- Crea un nuovo progetto Rust binario o di libreria nella directory specificata:

`cargo new {{percorso/della/directory}} --{{bin|lib}}`

- Builda il progetto Rust nella directory corrente:

`cargo {{[b|build]}}`

- Builda utilizzando più job (thread) paralleli:

`cargo {{[b|build]}} --jobs {{numero_job}}`
