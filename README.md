# Experimental Integrity Validator

A Python project for checking whether recorded experimental runs are consistent with an expected experimental design.

## Purpose

Experimental records can contain missing runs, unexpected runs, incorrect condition assignments, or inconsistent frequencies of experimental conditions.

This validator aims to identify these discrepancies and report which run IDs are involved.

## Current development status

**Work in progress — early prototype.**

The current Python implementation includes:

- Detection of missing run IDs
- Detection of unexpected run IDs
- Detection of mismatched condition assignments
- Grouping recorded runs by condition combination
- Identification of repeated recorded conditions

## Planned improvements

- Compare expected and recorded condition frequencies
- Distinguish intentional repeated conditions from discrepancies
- Improve discrepancy reporting
- Test edge cases and document limitations
- Publish a tested version of the Python script

## Scope and limitations

This tool checks the internal consistency of experimental records. It does not establish whether an experiment actually occurred or whether its results are scientifically valid.

## Technology

Python 3, using standard dictionaries, tuples, lists, and loops.
