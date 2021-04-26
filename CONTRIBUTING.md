# Contribution Guide

This is a guide for contributing to ospc-dimm.

## Base Template

You should use `ospc-ddr4-udimm-1r-x16-t` as a base for your project. Please use note texts from that project (decoupland, etc.) in your new design.

## Adding libraries/modules

Please add libraries & modules into the root modules and libraries folder, and add them to your project with a project-level include.

## Adding Net Classes for Fab limits

If you add a net class for a specific PCB fab, please add it to all other subprojects too.