---
published: true
title: OLAP Servers - Uncomplicating Data Processing
layout: post
---
Online Analytical Processing, or OLAP, is a technique of providing end users with quick access to vast amounts of data. OLAP servers use multidimensional data representations (also known as cubes) to facilitate this access to data that is stored in data warehouses. These cubes arrange data in the dimension and fact tables in a data warehouse, so as to provide high-end query and analysis features to client applications. The software used in these servers also gives users real-time data analysis capabilities for information stored in warehouses.
An OLAP server basically plays its role as a separate component and houses indexing tools and algorithms to enable fast processing of data mining tasks without hampering database performance. OLAP is actually a very vital part of any business, since it helps in the analysis and decision making process. Apt examples of this are IT organizations, which are often having problems related to systems that depend on accurate information on decision making regarding numerous platforms and domains. These decision support systems are actually OLAP systems that provide this kind of information to assist decision makers in taking the right course of action for the benefit of the organization. OLAP servers basically aid in:
Data analysis from different business dimensions.
Supporting high-end analysis needs for effective decision making.
Supporting complicated analysis with atomic level data sets.
OLAP servers / systems are based on two kinds of architectures – Relational OLAP (ROLAP) and Multidimensional OLAP (MOLAP). ROLAP accesses data from the warehouses directly, while MOLAP implements a multidimensional database for providing analysis. Here's a brief analysis of both:
ROLAP architecture is not affected by the vast amounts of data stored on the database, and gives the choice to the system designer whether he wants to lay emphasis on batch processing requirements or query response time. MOLAP, on the other hand, requires pre-compilation of databases for optimum query performance so as to increase batch processing requirements.
ROLAP is better for dynamic consolidation for decision support analysis, and MOLAP suits batch consolidation of data.
ROLAP can be scaled to a greater number of business dimensions compared to MOLAP.
ROLAP has better support for OLAP analysis for vast amounts of atomic level data, while MOLAP delivers optimum performance when input data is small.
from http://www.goodarticle.info/Article/Technology/Databases/201510/64479.html