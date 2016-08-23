# Codeigniter-live-search
Codeigniter live search using ajax


CREATE TABLE `item` (
  `id` int(10) NOT NULL,
  `title` varchar(100) NOT NULL,
  `description` varchar(250) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;


--
-- Indexes for table `item`
--
ALTER TABLE `item`
  ADD PRIMARY KEY (`id`);



--
-- AUTO_INCREMENT for table `item`
--
ALTER TABLE `item`
  MODIFY `id` int(10) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=10;



--
-- Dumping data for table `item`
--

INSERT INTO `item` (`id`, `title`, `description`) VALUES
(4, 'item-1', 'item-1'),
(7, 'item-2', 'item-2'),
(8, 'item-3', 'item-3'),
(9, 'item-4', 'item-4');

