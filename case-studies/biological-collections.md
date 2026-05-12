# Samples in biological collections

## About biological collections

Biological collections - including vertebrates (birds, mammals,
reptiles fish), invertebrates (insets), herbarium (pressed and dried
plant specimens, cryptogams, fungi), and algae (living collection).

## Samples in biological collections

Typically the collection consists of physical specimens, also referred
to as voucher specimens.  They can be the "whole body" of a zoological
specimen, or a pinned insect, or a representative sample of a plant
that has been dried and preserved.  There can also be associated
partial sample types such as a wing or a leg or a bone, or the sample
may be preserved in ethanol or at low temperature.  There may also be
genetic tissue samples linked to the physical specimen.

## Characterising properties

Our "Samples" are generally divided into a hierarchy structure.  The
top level is the "collection object" which generally describes the
vouchered specimen, and has the taxonomic determination, and locality
details attached to it (along with other metadata where relevant such
as voucher relationships, additional IDs etc.).  Each of our
collection objects can have multiple "preparations" which detail the
type of specimen, such as whole body, leg, wing, preserved sheet,
primary strain, liver tissue sample etc. These preparations also have
linked properties such as physical storage details, and potentially
loan/exchange history.  Beneath that, any preparation can have
multiple samples that are used for research that might have sequence
data attached, or other experimental results.

## Vocabularies and metadata standards

darwin core (https://dwc.tdwg.org/) is our metadata standards for
exporting data to the public via aggregators such a the ALA
(https://www.ala.org.au/) and GBIF (https://www.gbif.org/)

## Sample PIDs being used

Each collection has their own unique ID - a Catalog Number - to
represent a specimen.  Some collections also have unique preparation
Numbers as well.  When we supply information about the specimens
externally (to the ALA) the Catalog Number is combined with the unique
Collection Code to form a globally unique identifier.
