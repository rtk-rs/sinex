SINEX
=====

[![Rust](https://github.com/rtk-rs/sinex/actions/workflows/rust.yml/badge.svg)](https://github.com/rtk-rs/sinex/actions/workflows/rust.yml)
[![Rust](https://github.com/rtk-rs/sinex/actions/workflows/daily.yml/badge.svg)](https://github.com/rtk-rs/sinex/actions/workflows/daily.yml) [![crates.io](https://img.shields.io/crates/v/sinex.svg)](https://crates.io/crates/sinex) 
[![crates.io](https://docs.rs/sinex/badge.svg)](https://docs.rs/sinex/badge.svg)

[![License](https://img.shields.io/badge/license-MPL_2.0-orange?style=for-the-badge&logo=mozilla)](https://github.com/rtk-rs/sinex/blob/main/LICENSE)

SINEX is an open source format to describe Bias Solutions, needed in a high precision PPP geodetic pipeline.  

This library provides a parser for this very format.

Behavior:

* this parser does not care about file naming conventions
* the parser expects proper Header and SINEX structures
* the parser only cares about the Header position
* the parser does not care about the Description / Solution order
* the parse does not care about the Description fields order, as specified by standards
